﻿---
Description: 'Remotable version of the IMFSourceResolver::BeginCreateObjectFromByteStream method.'
ms.assetid: '960b5c51-b9b1-4956-a270-abfb7eedd482'
title: RemoteBeginCreateObjectFromByteStream
---

# RemoteBeginCreateObjectFromByteStream

Remotable version of the [**IMFSourceResolver::BeginCreateObjectFromByteStream**](imfsourceresolver-begincreateobjectfrombytestream.md) method.

``` syntax
[call_as(BeginCreateObjectFromByteStream)]
HRESULT RemoteBeginCreateObjectFromByteStream(
    IMFByteStream* pByteStream,
    LPCWSTR pwszURL,
    IPropertyStore *pProps,
    DWORD dwFlags,
    IMFRemoteAsyncCallback *pCallback
);
```

## Remarks

Applications cannot call this method directly, and objects do not implement this method. The method does not appear in the vtable for the interface. If [**BeginCreateObjectFromByteStream**](imfsourceresolver-begincreateobjectfrombytestream.md) is called across process boundaries, the Media Foundation proxy/stub DLL translates the call into a call to the remote method and then translates it back.

## Requirements



|                                     |                                                                                                          |
|-------------------------------------|----------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps \| UWP apps\]<br/>                                                    |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps \| UWP apps\]<br/>                                              |
| Header<br/>                   | <dl> <dt>Mfobjects.h (include Mfidl.h)</dt> </dl> |
| Library<br/>                  | <dl> <dt>Mfuuid.lib</dt> </dl>                    |



## See also

<dl> <dt>

[**IMFSourceResolver**](imfsourceresolver.md)
</dt> </dl>

 

 



