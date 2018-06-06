---
title: Bluetooth and getaddrinfo
description: The getaddrinfo function provides translation from host name to address for IP-based transports. Because the getaddrinfo function is specific to IP-based transports, it fails on Bluetooth sockets.
ms.assetid: e17d8542-d4bc-499c-bae4-1f41bff493c3
keywords:
- Bluetooth and getaddrinfo Bluetooth
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Bluetooth and getaddrinfo

The [**getaddrinfo**](https://msdn.microsoft.com/library/windows/desktop/ms738520) function provides translation from host name to address for IP-based transports. Because the **getaddrinfo** function is specific to IP-based transports, it fails on Bluetooth sockets.

To perform translation from host name to address for Bluetooth sockets, use the [**WSALookupServiceBegin**](bluetooth-and-wsalookupservicebegin-for-device-inquiry.md) function with **LUP\_CONTAINERS** to query remote devices, then search for a specific matching Remote Name and corresponding address.

## Related topics

<dl> <dt>

[Windows Sockets](https://msdn.microsoft.com/library/windows/desktop/ms740673)
</dt> <dt>

[**getaddrinfo**](https://msdn.microsoft.com/library/windows/desktop/ms738520)
</dt> <dt>

[**WSALookupServiceBegin**](https://msdn.microsoft.com/library/windows/desktop/ms741633)
</dt> </dl>

 

 



