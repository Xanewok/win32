---
title: Getting ADSI Interfaces From Your Extension
description: An extension often needs to get data from the directory object it binds to.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\mbaldwin
ms.assetid: '2d2e6dc6-1eed-491b-9d6a-7f35c24a7ba8'
ms.prod: 'windows-server-dev'
ms.technology: 'active-directory-domain-services'
ms.tgt_platform: multiple
keywords: ["extensions ADSI ,getting ADSI interfaces from your extension", "ADSI ADSI ,example code C/C++ ,getting ADSI interfaces from your extension"]
---

# Getting ADSI Interfaces From Your Extension

An extension often needs to get data from the directory object it binds to. For example, an extension for a **computer** object may want to get the **dnsHostName** of the current object from the directory. This can be easily achieved by issuing a **QueryInterface** call on the [**IUnknown**](_com_iunknown) interface for the aggregator.


```C++
HRESULT hr;
IADs *pADs; ' ADSI Interface to get/set attributes.
 
hr = m_pOuterUnk->QueryInterface(IID_IADs,(void**)&amp;pADs);
 
if ( SUCCEEDED(hr) )
{
    VARIANT var;
    VariantInit(&amp;var);
    hr  = pADs ->Get(_bstr_t("dnsHostName"), &amp;var);
    if ( SUCCEEDED(hr) )
    { 
        printf("%S\n", V_BSTR(&amp;var));
    }
    VariantClear(&amp;var);
    pADs->Release();
}
```



You should release the interface immediately after using it. If the extension has an open reference to the aggregator, you have created a circular reference and the aggregator cannot release the extension. Therefore, the aggregator cannot be released and the result is memory leaks in your application.

 

 



