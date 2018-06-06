---
Description: 'Returns the Cryptography API: Next Generation (CNG) Algorithm Identifier of the hashing algorithm that is used for the Transport Layer Security protocol (TLS) pseudo-random function (PRF) for the input protocol, cipher suite, and key type.'
ms.assetid: 8d20b2da-390e-458e-b122-f5ef3722ad87
title: SslGetCipherSuitePRFHashAlgorithm function
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# SslGetCipherSuitePRFHashAlgorithm function

The **SslGetCipherSuitePRFHashAlgorithm** function returns the Cryptography API: Next Generation (CNG) Algorithm Identifier of the [*hashing algorithm*](https://msdn.microsoft.com/library/windows/desktop/ms721586#-security-hashing-algorithm-gly) that is used for the [*Transport Layer Security protocol*](https://msdn.microsoft.com/library/windows/desktop/ms721627#-security-transport-layer-security-protocol-gly) (TLS) [*pseudo-random function*](https://msdn.microsoft.com/library/windows/desktop/ms721603#-security-pseudo-random-function-gly) (PRF) for the input protocol, cipher suite, and key type.

## Syntax


```C++
SECURITY_STATUS WINAPI SslGetCipherSuitePRFHashAlgorithm(
  _In_  NCRYPT_PROV_HANDLE hSslProvider,
  _In_  DWORD              dwProtocol,
  _In_  DWORD              dwCipherSuite,
  _In_  DWORD              dwKeyType,
  _Out_ WCHAR              szPRFHash[NCRYPT_SSL_MAX_NAME_SIZE],
  _In_  DWORD              dwFlags
);
```



## Parameters

<dl> <dt>

*hSslProvider* \[in\]
</dt> <dd>

The handle of the [*Secure Sockets Layer protocol*](https://msdn.microsoft.com/library/windows/desktop/ms721625#-security-secure-sockets-layer-protocol-gly) (SSL) protocol provider instance.

</dd> <dt>

*dwProtocol* \[in\]
</dt> <dd>

One of the [**CNG SSL Provider Protocol Identifier**](https://www.bing.com/search?q=**CNG+SSL+Provider+Protocol+Identifier**) values.

</dd> <dt>

*dwCipherSuite* \[in\]
</dt> <dd>

One of the [**CNG SSL Provider Cipher Suite Identifier**](https://www.bing.com/search?q=**CNG+SSL+Provider+Cipher+Suite+Identifier**) values.

</dd> <dt>

*dwKeyType* \[in\]
</dt> <dd>

One of the [**CNG SSL Provider Key Type Identifier**](https://www.bing.com/search?q=**CNG+SSL+Provider+Key+Type+Identifier**) values. For key types that are not [*elliptic curve cryptography*](https://msdn.microsoft.com/library/windows/desktop/ms721575#-security-elliptic-curve-cryptography-gly) (ECC), set this parameter to zero.

</dd> <dt>

*szPRFHash* \[out\]
</dt> <dd>

One of the [**CNG Algorithm Identifiers**](cng-algorithm-identifiers.md) for the hash that will be used for the TLS PRF.

</dd> <dt>

*dwFlags* \[in\]
</dt> <dd>

This parameter is reserved for future use and must be set to zero.

</dd> </dl>

## Return value

If the function succeeds, it returns zero.

If the function fails, it returns a nonzero error value.

Possible return codes include, but are not limited to, the following.



| Return code/value                                                                                                                                                       | Description                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| <dl> <dt>**NTE\_INVALID\_HANDLE**</dt> <dt>0x80090026L</dt> </dl>    | The *hSslProvider* parameter contains a pointer that is not valid.<br/>                |
| <dl> <dt>**NTE\_INVALID\_PARAMETER**</dt> <dt>0x80090027L</dt> </dl> | The *szPRFHash* parameter is set to **NULL**.<br/>                                     |
| <dl> <dt>**NTE\_NOT\_SUPPORTED**</dt> <dt>0x80090029L</dt> </dl>     | The selected function is not supported in the specified version of the interface.<br/> |
| <dl> <dt>**NTE\_BAD\_FLAGS**</dt> <dt>0x80090009L</dt> </dl>         | The *dwFlags* parameter must be set to zero.<br/>                                      |



 

## Remarks

This **SslGetCipherSuitePRFHashAlgorithm** function is called for TLS 1.2 or later conversations to query the hashing algorithm that will be used in the TLS PRF.

## Requirements



|                                     |                                                                                          |
|-------------------------------------|------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/>                                               |
| Minimum supported server<br/> | Windows Server 2008 R2 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Sslprovider.h</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Ncrypt.dll</dt> </dl>    |



 

 



