﻿---
Description: 'Retrieves the key specification.'
ms.assetid: '93c909cb-b1d1-4c2b-a66c-9d3f6dd9b340'
title: 'PrivateKey.KeySpec property'
---

# PrivateKey.KeySpec property

\[The **KeySpec** property is available for use in the operating systems specified in the Requirements section. Instead, use the [**X509Certificate2.PrivateKey Property**](frlrfSystemSecurityCryptographyX509CertificatesX509Certificate2ClassPrivateKeyTopic) in the [**System.Security.Cryptography.X509Certificates**](frlrfSystemSecurityCryptographyX509Certificates) namespace.\]

The **KeySpec** property retrieves the key specification.

## Syntax


```VB
PrivateKey.KeySpec As CAPICOM_KEY_SPEC
```



## Property value

A value of the [**CAPICOM\_KEY\_SPEC**](capicom-key-spec.md) enumeration that indicates the key specification. The following table shows the possible values.



| Value                                                                                                                                                                                                        | Meaning                                                    |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| <span id="CAPICOM_KEY_SPEC_KEYEXCHANGE"></span><span id="capicom_key_spec_keyexchange"></span><dl> <dt>**CAPICOM\_KEY\_SPEC\_KEYEXCHANGE**</dt> </dl> | The key can be used for encryption and signing.<br/> |
| <span id="CAPICOM_KEY_SPEC_SIGNATURE"></span><span id="capicom_key_spec_signature"></span><dl> <dt>**CAPICOM\_KEY\_SPEC\_SIGNATURE**</dt> </dl>       | The key can be used only for signing.<br/>           |



 

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**PrivateKey**](privatekey.md)
</dt> </dl>

 

 



