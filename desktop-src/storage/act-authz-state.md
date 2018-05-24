---
title: ACT\_AUTHZ\_STATE structure
description: This structure describes the Addressable Command Target (ACT) authorization state.
ms.assetid: '32bb774f-b1eb-4198-8e4c-febcac83153d'
keywords: ["ACT_AUTHZ_STATE structure Storage Devices", "PACT_AUTHZ_STATE structure pointer Storage Devices"]
topic_type:
- apiref
api_name:
- ACT_AUTHZ_STATE
api_location:
- EhStorIoctl.h
api_type:
- HeaderDef
---

# ACT\_AUTHZ\_STATE structure

This structure describes the Addressable Command Target (ACT) authorization state.

## Syntax


```C++
typedef struct tagACT_AUTHZ_STATE {
  UCHAR ��ACT;
  BOOLEAN fAuthorized;
} ACT_AUTHZ_STATE, *PACT_AUTHZ_STATE;
```



## Members

<dl> <dt>

**ACT**
</dt> <dd>

This member is ignored.

</dd> <dt>

**fAuthorized**
</dt> <dd>

This member may be either **TRUE** (authorized) or **FALSE** (not authorized).

</dd> </dl>

## Remarks

## Requirements



|                   |                                                                                                                  |
|-------------------|------------------------------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>EhStorIoctl.h (include EhStorIoctl.h)</dt> </dl> |



�

�

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bstorage\storage%5D:%20ACT_AUTHZ_STATE%20structure%20%20RELEASE:%20%283/29/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




