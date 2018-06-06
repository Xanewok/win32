---
Description: The EffectsEnabled method determines whether effects are enabled. If effects are disabled, they remain in the timeline but are not rendered.
ms.assetid: fd8bb2aa-9c10-4a85-9e9d-1b342fbce03b
title: IAMTimeline::EffectsEnabled method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# IAMTimeline::EffectsEnabled method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `EffectsEnabled` method determines whether effects are enabled. If effects are disabled, they remain in the timeline but are not rendered.

## Syntax


```C++
HRESULT EffectsEnabled(
   BOOL *pfEnabled
);
```



## Parameters

<dl> <dt>

*pfEnabled* 
</dt> <dd>

Receives a Boolean value indicating whether effects are enabled. If **TRUE**, effects are enabled. If **FALSE**, effects are disabled.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](http://go.microsoft.com/fwlink/p/?linkid=129787). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IAMTimeline Interface**](iamtimeline.md)
</dt> <dt>

[Error and Success Codes](error-and-success-codes.md)
</dt> </dl>

 

 



