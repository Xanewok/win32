---
Description: 'The following enumerations are supported by the Certificate Enrollment API.'
ms.assetid: '8514fb89-1cf5-4e09-997c-17984efc4e03'
title: CertEnroll Enumerations
---

# CertEnroll Enumerations

The following enumerations are supported by the Certificate Enrollment API.

| Enumeration                                                                              | Description                                                                                                                                                                                                                                                                                                              |
|------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**AlgorithmFlags**](algorithmflags-enum.md)                                            | Contains flags that can be used to refine the search for a cryptographic algorithm.                                                                                                                                                                                                                                      |
| [**AlgorithmOperationFlags**](algorithmoperationflags-enum.md)                          | Specifies the operations that an algorithm can perform. This is used to retrieve the operational capabilities of a CSP algorithm or CSP status information based on those capabilities.                                                                                                                                  |
| [**AlgorithmType**](algorithmtype-enum.md)                                              | Specifies the intended purpose of a cryptographic algorithm.                                                                                                                                                                                                                                                             |
| [**AlternativeNameType**](alternativenametype-enum.md)                                  | Specifies the alternative name types that can be specified when creating an **AlternativeName** extension.                                                                                                                                                                                                               |
| [**CERTENROLL\_OBJECTID**](certenroll-objectid-enum.md)                                 | Contains the predefined [*object identifiers*](https://msdn.microsoft.com/library/windows/desktop/ms721599#-security-object-identifier-gly) (OIDs) supported the Certificate Enrollment API.                                                                                                                                          |
| [**CERTENROLL\_PROPERTYID**](certenroll-propertyid-enum.md)                             | Contains predefined OIDs for external properties supported by the Certificate Enrollment API.                                                                                                                                                                                                                            |
| [**CommitTemplateFlags**](committemplateflags.md)                                       | Specifies options for saving and deleting templates.                                                                                                                                                                                                                                                                     |
| [**EncodingType**](encodingtype-enum.md)                                                | Specifies the type of encoding applied to a byte array for display purposes.                                                                                                                                                                                                                                             |
| [**EnrollmentCAProperty**](enrollmentcaproperty.md)                                     | Specifies certification authority property values.                                                                                                                                                                                                                                                                       |
| [**EnrollmentDisplayStatus**](enrollmentdisplaystatus-enum.md)                          | Specifies whether to display enrollment status information in a user interface.                                                                                                                                                                                                                                          |
| [**EnrollmentEnrollStatus**](enrollmentenrollstatus-enum.md)                            | Specifies the enrollment status of a certificate request.                                                                                                                                                                                                                                                                |
| [**EnrollmentPolicyFlags**](enrollmentpolicyflags.md)                                   | Specifies group policy flags.                                                                                                                                                                                                                                                                                            |
| [**EnrollmentPolicyServerPropertyFlags**](enrollmentpolicyserverpropertyflags.md)       | Specifies the default policy server.                                                                                                                                                                                                                                                                                     |
| [**EnrollmentSelectionStatus**](enrollmentselectionstatus-enum.md)                      | Specifies whether the enrollment status of an object will be monitored during the enrollment process.                                                                                                                                                                                                                    |
| [**EnrollmentTemplateProperty**](enrollmenttemplateproperty.md)                         | Contains property values for a given template.                                                                                                                                                                                                                                                                           |
| [**InnerRequestLevel**](innerrequestlevel-enum.md)                                      | Specifies the containment level of a certificate request within a PKCS \#7 or CMC request.                                                                                                                                                                                                                               |
| [**InstallResponseRestrictionFlags**](installresponserestrictionflags-enum.md)          | Contains flags that identify the restrictions placed on the local installation of a certificate chain.                                                                                                                                                                                                                   |
| [**KeyIdentifierHashAlgorithm**](keyidentifierhashalgorithm-enum.md)                    | Specifies the algorithm used to hash the public key in a certificate request.                                                                                                                                                                                                                                            |
| [**ObjectIdGroupId**](objectidgroupid-enum.md)                                          | Specifies the category or group to which an OID belongs.                                                                                                                                                                                                                                                                 |
| [**ObjectIdPublicKeyFlags**](objectidpublickeyflags-enum.md)                            | Specifies whether a public key algorithm is used for signing or for encryption.                                                                                                                                                                                                                                          |
| [**PFXExportOptions**](pfxexportoptions-enum.md)                                        | Specifies how much of a certificate chain is included when creating a Personal Information Exchange (PFX) message.                                                                                                                                                                                                       |
| [**Pkcs10AllowedSignatureTypes**](pkcs10allowedsignaturetypes-enum.md)                  | Specifies the type of signature permitted when signing a certificate request.                                                                                                                                                                                                                                            |
| [**PolicyQualifierType**](policyqualifiertype-enum.md)                                  | Specifies the type of qualifier applied to a certificate policy.                                                                                                                                                                                                                                                         |
| [**PolicyServerUrlFlags**](policyserverurlflags.md)                                     | Contains certificate enrollment policy (CEP) server flags.                                                                                                                                                                                                                                                               |
| [**PolicyServerUrlPropertyID**](policyserverurlpropertyid.md)                           | Contains values that specify the type of property value to be returned by the [**GetStringProperty**](ix509policyserverurl-getstringproperty.md) method or set by the [**SetStringProperty**](ix509policyserverurl-setstringproperty.md) method on the [**IX509PolicyServerUrl**](ix509policyserverurl.md) interface. |
| [**RequestClientInfoClientId**](requestclientinfoclientid-enum.md)                      | Specifies the type of application that created a certificate request.                                                                                                                                                                                                                                                    |
| [**WebEnrollmentFlags**](webenrollmentflags.md)                                         | Specifies web enrollment behavior.                                                                                                                                                                                                                                                                                       |
| [**WebSecurityLevel**](websecuritylevel-enum.md)                                        | Specifies whether a web-enabled method or property is safe for scripting.                                                                                                                                                                                                                                                |
| [**X500NameFlags**](x500nameflags-enum.md)                                              | Specifies the display and encoding characteristics of a distinguished name or relative distinguished name.                                                                                                                                                                                                               |
| [**X509CertificateEnrollmentContext**](x509certificateenrollmentcontext-enum.md)        | Specifies the nature of the end entity for which the certificate is intended.                                                                                                                                                                                                                                            |
| [**X509CertificateTemplateEnrollmentFlag**](x509certificatetemplateenrollmentflag.md)   | Contains values that specify server and client actions during enrollment.                                                                                                                                                                                                                                                |
| [**X509CertificateTemplateGeneralFlag**](x509certificatetemplategeneralflag.md)         | Contains use and modification information about templates and associated certificates.                                                                                                                                                                                                                                   |
| [**X509CertificateTemplatePrivateKeyFlag**](x509certificatetemplateprivatekeyflag.md)   | Contains values that specify client actions regarding a private key.                                                                                                                                                                                                                                                     |
| [**X509CertificateTemplateSubjectNameFlag**](x509certificatetemplatesubjectnameflag.md) | Contains values that specify server and client actions concerning subject names.                                                                                                                                                                                                                                         |
| [**X509EnrollmentPolicyExportFlags**](x509enrollmentpolicyexportflags.md)               | Specifies what items to export from the policy server.                                                                                                                                                                                                                                                                   |
| [**X509EnrollmentPolicyLoadOption**](x509enrollmentpolicyloadoption.md)                 | Specifies how to retrieve policy from the policy server.                                                                                                                                                                                                                                                                 |
| [**X509KeySpec**](x509keyspec-enum.md)                                                  | Specifies the intended use of a key for a legacy CSP.                                                                                                                                                                                                                                                                    |
| [**X509KeyUsageFlags**](x509keyusageflags-enum.md)                                      | Specifies the purpose of a key contained in a certificate.                                                                                                                                                                                                                                                               |
| [**X509PrivateKeyExportFlags**](x509privatekeyexportflags.md)                           | Specifies the export policy for a private key.                                                                                                                                                                                                                                                                           |
| [**X509PrivateKeyProtection**](x509privatekeyprotection.md)                             | Specifies the level of private key protection supported by a KSP or CSP.                                                                                                                                                                                                                                                 |
| [**X509PrivateKeyUsageFlags**](x509privatekeyusageflags.md)                             | Specifies the permitted uses of a private key.                                                                                                                                                                                                                                                                           |
| [**X509PrivateKeyVerify**](x509privatekeyverify.md)                                     | Specifies whether a user interface is displayed during private key verification and whether verification can proceed if the CSP or KSP represent a smart card.                                                                                                                                                           |
| [**X509ProviderType**](x509providertype-enum.md)                                        | Specifies the type of a cryptographic service provider or key service provider.                                                                                                                                                                                                                                          |
| [**X509RequestInheritOptions**](x509requestinheritoptions-enum.md)                      | Specifies how keys, extension values, and external properties are inherited when a new request is created from an existing certificate.                                                                                                                                                                                  |
| [**X509RequestType**](x509requesttype-enum.md)                                          | Specifies the certificate request type.                                                                                                                                                                                                                                                                                  |
| [**X509SCEPDisposition**](x509scepdisposition.md)                                       | Describes the resulting disposition of a request to process a response message.                                                                                                                                                                                                                                          |
| [**X509SCEPFailInfo**](x509scepfailinfo.md)                                             | Describes the nature of an SCEP certificate enrollment failure.                                                                                                                                                                                                                                                          |



 

## Related topics

<dl> <dt>

[Certificate Enrollment API Reference](certificate-enrollment-api-reference.md)
</dt> <dt>

[CertEnroll Interfaces](certenroll-interfaces.md)
</dt> </dl>

 

 


