---
title: IVMFloppyDriveEvents OnMediaEject method
description: Called when media has been ejected from the drive.
ms.assetid: '928b2f61-98a1-406f-959b-db5fecd0ba2a'
keywords: ["OnMediaEject method Virtual Server", "OnMediaEject method Virtual Server , IVMFloppyDriveEvents interface", "IVMFloppyDriveEvents interface Virtual Server , OnMediaEject method", "OnMediaEject method Virtual Server , VMFloppyDrive interface", "VMFloppyDrive interface Virtual Server , OnMediaEject method"]
topic_type:
- apiref
api_name:
- IVMFloppyDriveEvents.OnMediaEject
- VMFloppyDrive.OnMediaEject
api_location:
- VsComInterfaces.h
api_type:
- COM
---

# IVMFloppyDriveEvents::OnMediaEject method

The **OnMediaEject** method is called when media has been ejected from the drive.

## Syntax


```C++
HRESULT OnMediaEject(
  [in]�BSTR     mediaPath
);
```



## Parameters

<dl> <dt>

 *mediaPath* \[in\]
</dt> <dd>

The host drive letter, or path, to floppy image.

</dd> </dl>

## Return value

A [**32-bit value**](hresult-codes-specific-to-the-virtual-server.md) that describes an error or warning.

## Remarks

This method is called when media (a floppy disk image or a floppy disk in a host drive) is ejected. The client program must implement this interface method to receive notification of the [**vmFloppyDriveEvent\_OnMediaEject**](vmfloppydriveevent.md) event originating from [**IVMFloppyDrive**](ivmfloppydrive.md).

## Requirements



|                     |                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| Product<br/>  | Microsoft Virtual Server 2005 onWindows Server�2003<br/>                                    |
| Download<br/> | Microsoft Virtual Server 2005 R2 SP1 Update onWindows Server�2008orWindows Server�2003<br/> |
| Header<br/>   | <dl> <dt>VsComInterfaces.h</dt> </dl>      |



## See also

<dl> <dt>

[**IVMFloppyDriveEvents**](ivmfloppydriveevents.md)
</dt> </dl>

�

�




