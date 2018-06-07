---
Description: The EngUnmapFontFile function is obsolete. Use EngUnmapFontFileFD instead.
ms.assetid: 0fc34dfe-fbe8-4bee-8766-4b1db9b5ccfa
title: EngUnmapFontFile
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# EngUnmapFontFile

The **EngUnmapFontFile** function is **obsolete**. Use [**EngUnmapFontFileFD**](/windows/desktop/api/winddi/nf-winddi-engunmapfontfilefd) instead.

``` syntax
    VOID
      EngUnmapFontFile(
     ULONG_PTR 
    iFile
      );
   
```

## Requirements



|                    |                                                                                                        |
|--------------------|--------------------------------------------------------------------------------------------------------|
| Version<br/> | Available in Windows 2000 and later versions of the Windows operating systems.<br/>              |
| Header<br/>  | <dl> <dt>Winddi.h (include Winddi.h)</dt> </dl> |
| Library<br/> | <dl> <dt>Win32k.lib</dt> </dl>                  |
| DLL<br/>     | <dl> <dt>Win32k.sys</dt> </dl>                  |



 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bdisplay\display%5D:%20EngUnmapFontFile%20%20RELEASE:%20%285/12/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/en-us/default.aspx. "Send comments about this topic to Microsoft")



