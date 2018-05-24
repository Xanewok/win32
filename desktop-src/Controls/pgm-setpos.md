---
title: PGM\_SETPOS message
description: Sets the current scroll position for the pager control. You can send this message explicitly or use the Pager\_SetPos macro.
ms.assetid: 'b882ea2d-9dab-4d36-9201-29522141f779'
keywords: ["PGM_SETPOS message Windows Controls"]
topic_type:
- apiref
api_name:
- PGM_SETPOS
api_location:
- Commctrl.h
api_type:
- HeaderDef
---

# PGM\_SETPOS message

Sets the current scroll position for the pager control. You can send this message explicitly or use the [**Pager\_SetPos**](pager-setpos.md) macro.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>Must be zero.</dd> <dt>

*lParam* 
</dt> <dd>

Value of type **int** that contains the new scroll position, in pixels.

</dd> </dl>

## Return value

The return value is not used.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



�

�




