# [Structured Storage](structured-storage-start-page.md)
## [About Structured Storage](about-structured-storage.md)
### [Benefits of Structured Storage](benefits-of-structured-storage.md)
#### [The Evolution of File Systems](the-evolution-of-file-systems.md)
#### [Storages and Streams](storages-and-streams.md)
#### [Compound Files](compound-files.md)
### [Structured Storage Fundamentals](structured-storage-fundamentals.md)
#### [COM Objects and Structured Storage](com-objects-and-structured-storage.md)
#### [Storage Object Naming Conventions](storage-object-naming-conventions.md)
#### [Structured Storage Interfaces](structured-storage-interfaces.md)
#### [Structured Storage API Functions](structured-storage-api-functions.md)
##### [Structured Storage Access Modes](structured-storage-access-modes.md)
###### [Transaction Flags](transaction-flags.md)
###### [Storage Creation Flags](storage-creation-flags.md)
###### [Temporary Creation Flags](temporary-creation-flags.md)
###### [Priority Flags](priority-flags.md)
###### [Access Permission Flags](access-permission-flags.md)
###### [Shared Access Flags](shared-access-flags.md)
#### [Properties and Property Sets](properties-and-property-sets.md)
##### [The Summary Information Property Set](the-summary-information-property-set.md)
##### [Predefined Property Set Format Identifiers](predefined-property-set-format-identifiers.md)
##### [The DocumentSummaryInformation and UserDefined Property Sets](the-documentsummaryinformation-and-userdefined-property-sets.md)
#### [Structured Storage Serialized Property Set Format](structured-storage-serialized-property-set-format.md)
##### [Property Set Header](property-set-header.md)
###### [Byte-Order Indicator](byte-order-indicator.md)
###### [Format Version](format-version.md)
###### [Operating System Versions](operating-system-versions.md)
###### [Class Identifier](class-identifier.md)
###### [Reserved](reserved.md)
##### [Format Identifier/Offset Pair](format-identifier-offset-pair.md)
###### [Format Identifiers](format-identifiers.md)
###### [Allocating Format Identifiers](allocating-format-identifiers.md)
##### [Section](section.md)
###### [Size of Section](size-of-section.md)
###### [Count of Properties](count-of-properties.md)
###### [Property Identifiers/Offset Pairs](property-identifiers-offset-pairs.md)
###### [Type Indicators](type-indicators.md)
##### [Reserved Property Identifiers](reserved-property-identifiers.md)
###### [Property Set Display Name Dictionary](property-set-display-name-dictionary.md)
### [Asynchronous Storage](asynchronous-storage.md)
#### [Storage Modes](storage-modes.md)
#### [Asynchronous Compound Files](asynchronous-compound-files.md)
#### [How Asynchronous Binding and Storage Work](how-asynchronous-binding-and-storage-work.md)
#### [Compound File Optimization](compound-file-optimization.md)
## [Using Structured Storage](using-structured-storage.md)
### [How to Build Samples](how-to-build-samples.md)
#### [Environment Setup](environment-setup.md)
#### [Makefiles](makefiles.md)
#### [Using Visual Studio](using-visual-studio.md)
#### [Extracting the Code Samples](extracting-the-code-samples.md)
#### [Coding Style Conventions](coding-style-conventions.md)
### [Structured Storage Samples](structured-storage-samples.md)
#### [Structured Storage Client Sample (StoClien)](structured-storage-client-sample--stoclien-.md)
##### [StoClien Overview](stoclien-overview.md)
###### [StoClien Operations](stoclien-operations.md)
##### [Create and Run StoClien Sample](create-and-run-stoclien-sample.md)
###### [CGuiPaper Class Declaration](cguipaper-class-declaration.md)
###### [CGuiPaper Methods](cguipaper-methods.md)
####### [InkStart Method](inkstart-method.md)
####### [InkDraw Method](inkdraw-method.md)
####### [PaintWin Method](paintwin-method.md)
###### [CMainWindow](cmainwindow.md)
###### [CPapFile Class and Methods](cpapfile-class-and-methods.md)
####### [Init Method - CPapFile](init-method---cpapfile.md)
####### [Save Method - CPapFile](save-method---cpapfile.md)
####### [Load Method - CPapFile](load-method---cpapfile.md)
#### [Structured Storage Server Sample (StoServe)](structured-storage-server-sample--stoserve-.md)
##### [StoServe Overview](stoserve-overview.md)
##### [Using StoServe](using-stoserve.md)
##### [Create and Run StoServe Sample](create-and-run-stoserve-sample.md)
###### [IPaper Methods](ipaper-methods.md)
####### [IPaper::Load](ipaper--load.md)
####### [IPaper::Redraw](ipaper--redraw.md)
####### [IPaper::Save](ipaper--save.md)
###### [IPaperSink Methods](ipapersink-methods.md)
###### [Structures - StoServe](structures---stoserve.md)
###### [Unicode Considerations](unicode-considerations.md)
### [Managing Properties](managing-properties.md)
#### [Property Storage Considerations](property-storage-considerations.md)
### [Managing Property Sets](managing-property-sets.md)
#### [Property Set Implementations in COM](property-set-implementations-in-com.md)
##### [Property Set Considerations](property-set-considerations.md)
###### [IPropertySetStorage Implementation Considerations](ipropertysetstorage-implementation-considerations.md)
####### [Names in IStorage](names-in-istorage.md)
####### [Storage and Stream Objects for a Property Set](storage-vs--stream-for-a-property-set.md)
####### [Setting the Property Set Class Identifier](setting-the-property-set-class-identifier.md)
####### [Synchronization Points](synchronization-points.md)
####### [Code Pages and Unicode Strings](code-pages-and-unicode-strings.md)
####### [Dictionary](dictionary.md)
####### [Extensions](extensions.md)
####### [Property Set Serialization](version-0-vs--version-1-property-set-serialization.md)
##### [Storing Property Sets](storing-property-sets.md)
##### [Performance Characteristics](performance-characteristics.md)
##### [Implementing the Summary Information Property Set](implementing-the-summary-information-property-set.md)
## [Structured Storage Reference](structured-storage-reference.md)
### [Interfaces](interfaces.md)
#### [IDirectWriterLock](/windows/win32/content/Objidl/nn-objidl-idirectwriterlock?branch=dev)
##### [HaveWriteAccess](/windows/win32/content/Objidl/nf-objidl-idirectwriterlock-havewriteaccess?branch=dev)
##### [ReleaseWriteAccess](/windows/win32/content/Objidl/nf-objidl-idirectwriterlock-releasewriteaccess?branch=dev)
##### [WaitForWriteAccess](/windows/win32/content/Objidl/nf-objidl-idirectwriterlock-waitforwriteaccess?branch=dev)
##### [IDirectWriterLock - Compound File Implementation](idirectwriterlock-compound-file-implementation.md)
#### [IEnumSTATPROPSETSTG](/windows/win32/content/propidlbase/nn-propidl-ienumstatpropsetstg?branch=dev)
##### [Clone](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropsetstg-clone?branch=dev)
##### [Next](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropsetstg-next?branch=dev)
##### [RemoteNext](/windows/win32/content/Propidl/?branch=dev)
##### [Reset](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropsetstg-reset?branch=dev)
##### [Skip](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropsetstg-skip?branch=dev)
##### [IEnumSTATPROPSETSTG - Compound File Implementation](ienumstatpropsetstg-compound-file-implementation.md)
#### [IEnumSTATPROPSTG](/windows/win32/content/propidlbase/nn-propidl-ienumstatpropstg?branch=dev)
##### [Clone](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropstg-clone?branch=dev)
##### [Next](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropstg-next?branch=dev)
##### [RemoteNext](/windows/win32/content/Propidl/?branch=dev)
##### [Reset](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropstg-reset?branch=dev)
##### [Skip](/windows/win32/content/propidlbase/nf-propidl-ienumstatpropstg-skip?branch=dev)
##### [IEnumSTATPROPSTG - Compound File Implementation](ienumstatpropstg-compound-file-implementation.md)
#### [IEnumSTATSTG](/windows/win32/content/Objidl/nn-objidl-ienumstatstg?branch=dev)
##### [Clone](/windows/win32/content/Objidl/nf-objidl-ienumstatstg-clone?branch=dev)
##### [Next](/windows/win32/content/Objidl/nf-objidl-ienumstatstg-next?branch=dev)
##### [RemoteNext](/windows/win32/content/Objidl/?branch=dev)
##### [Reset](/windows/win32/content/Objidl/nf-objidl-ienumstatstg-reset?branch=dev)
##### [Skip](/windows/win32/content/Objidl/nf-objidl-ienumstatstg-skip?branch=dev)
#### [IFillLockBytes](/windows/win32/content/Objidl/nn-objidl-ifilllockbytes?branch=dev)
##### [FillAppend](/windows/win32/content/Objidl/nf-objidl-ifilllockbytes-fillappend?branch=dev)
##### [FillAt](/windows/win32/content/Objidl/nf-objidl-ifilllockbytes-fillat?branch=dev)
##### [RemoteFillAppend](/windows/win32/content/Objidl/?branch=dev)
##### [RemoteFillAt](/windows/win32/content/Objidl/?branch=dev)
##### [SetFillSize](/windows/win32/content/Objidl/nf-objidl-ifilllockbytes-setfillsize?branch=dev)
##### [Terminate](/windows/win32/content/Objidl/nf-objidl-ifilllockbytes-terminate?branch=dev)
##### [IFillLockBytes - Implementation](ifilllockbytes-implementation.md)
#### [ILayoutStorage](/windows/win32/content/Objidl/nn-objidl-ilayoutstorage?branch=dev)
##### [BeginMonitor](/windows/win32/content/Objidl/nf-objidl-ilayoutstorage-beginmonitor?branch=dev)
##### [EndMonitor](/windows/win32/content/Objidl/nf-objidl-ilayoutstorage-endmonitor?branch=dev)
##### [LayoutScript](/windows/win32/content/Objidl/nf-objidl-ilayoutstorage-layoutscript?branch=dev)
##### [ReLayoutDocfile](/windows/win32/content/Objidl/nf-objidl-ilayoutstorage-relayoutdocfile?branch=dev)
##### [ReLayoutDocfileOnILockBytes](ilayoutstorage-relayoutdocfileonilockbytes.md)
#### [ILockBytes](/windows/win32/content/Objidl/nn-objidl-ilockbytes?branch=dev)
##### [Flush](/windows/win32/content/Objidl/nf-objidl-ilockbytes-flush?branch=dev)
##### [LockRegion](/windows/win32/content/Objidl/nf-objidl-ilockbytes-lockregion?branch=dev)
##### [ReadAt](/windows/win32/content/Objidl/nf-objidl-ilockbytes-readat?branch=dev)
##### [RemoteReadAt](/windows/win32/content/Objidl/?branch=dev)
##### [RemoteWriteAt](/windows/win32/content/Objidl/?branch=dev)
##### [SetSize](/windows/win32/content/Objidl/nf-objidl-ilockbytes-setsize?branch=dev)
##### [Stat](/windows/win32/content/Objidl/nf-objidl-ilockbytes-stat?branch=dev)
##### [UnlockRegion](/windows/win32/content/Objidl/nf-objidl-ilockbytes-unlockregion?branch=dev)
##### [WriteAt](/windows/win32/content/Objidl/nf-objidl-ilockbytes-writeat?branch=dev)
##### [ILockBytes - File-Based Implementation](ilockbytes-file-based-implementation.md)
##### [ILockBytes - Global Memory Implementation](ilockbytes-global-memory-implementation.md)
#### [IMemoryAllocator](imemoryallocator.md)
##### [Allocate](imemoryallocator-allocate.md)
##### [Free](imemoryallocator-free.md)
#### [IPropertySetStorage](/windows/win32/content/Propidl/nn-propidl-ipropertysetstorage?branch=dev)
##### [Create](/windows/win32/content/Propidl/nf-propidl-ipropertysetstorage-create?branch=dev)
##### [Delete](/windows/win32/content/Propidl/nf-propidl-ipropertysetstorage-delete?branch=dev)
##### [Enum](/windows/win32/content/Propidl/nf-propidl-ipropertysetstorage-enum?branch=dev)
##### [Open](/windows/win32/content/Propidl/nf-propidl-ipropertysetstorage-open?branch=dev)
##### [IPropertySetStorage-Compound File Implementation](ipropertysetstorage-compound-file-implementation.md)
##### [IPropertySetStorage-NTFS File System Implementation](ipropertysetstorage-ntfs-file-system-implementation.md)
##### [IPropertySetStorage-Stand-alone Implementation](ipropertysetstorage-stand-alone-implementation.md)
#### [IPropertyStorage](/windows/win32/content/Propidl/nn-propidl-ipropertystorage?branch=dev)
##### [Commit](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-commit?branch=dev)
##### [DeleteMultiple](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-deletemultiple?branch=dev)
##### [DeletePropertyNames](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-deletepropertynames?branch=dev)
##### [Enum](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-enum?branch=dev)
##### [ReadMultiple](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-readmultiple?branch=dev)
##### [ReadPropertyNames](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-readpropertynames?branch=dev)
##### [RemoteDeleteMultiple](/windows/win32/content/Propidl/?branch=dev)
##### [RemoteReadMultiple](/windows/win32/content/Propidl/?branch=dev)
##### [RemoteWriteMultiple](/windows/win32/content/Propidl/?branch=dev)
##### [Revert](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-revert?branch=dev)
##### [SetClass](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-setclass?branch=dev)
##### [SetTimes](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-settimes?branch=dev)
##### [Stat](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-stat?branch=dev)
##### [WriteMultiple](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-writemultiple?branch=dev)
##### [WritePropertyNames](/windows/win32/content/Propidl/nf-propidl-ipropertystorage-writepropertynames?branch=dev)
##### [IPropertyStorage - Compound File Implementation](ipropertystorage-compound-file-implementation.md)
##### [IPropertyStorage - NTFS File System Implementation](ipropertystorage-ntfs-file-system-implementation.md)
##### [IPropertyStorage - Stand-alone Implementation](ipropertystorage-stand-alone-implementation.md)
##### [Differences between Standalone and Compound File Implementations](differences-between-stand-alone-and-compound-file-implementations.md)
#### [IRootStorage](/windows/win32/content/Objidl/nn-objidl-irootstorage?branch=dev)
##### [SwitchToFile](/windows/win32/content/Objidl/nf-objidl-irootstorage-switchtofile?branch=dev)
##### [IRootStorage - Compound File Implementation](irootstorage-compound-file-implementation.md)
#### [ISequentialStream](/windows/win32/content/Objidl/nn-objidl-isequentialstream?branch=dev)
##### [Read](/windows/win32/content/Objidl/nf-objidl-isequentialstream-read?branch=dev)
##### [RemoteRead](/windows/win32/content/Objidl/?branch=dev)
##### [RemoteWrite](/windows/win32/content/Objidl/?branch=dev)
##### [Write](/windows/win32/content/Objidl/nf-objidl-isequentialstream-write?branch=dev)
#### [IStorage](/windows/win32/content/Objidl/nn-objidl-istorage?branch=dev)
##### [Commit](/windows/win32/content/Objidl/nf-objidl-istorage-commit?branch=dev)
##### [CopyTo](/windows/win32/content/Objidl/nf-objidl-istorage-copyto?branch=dev)
##### [CreateStorage](/windows/win32/content/Objidl/nf-objidl-istorage-createstorage?branch=dev)
##### [CreateStream](/windows/win32/content/Objidl/nf-objidl-istorage-createstream?branch=dev)
##### [DestroyElement](/windows/win32/content/Objidl/nf-objidl-istorage-destroyelement?branch=dev)
##### [EnumElements](/windows/win32/content/Objidl/nf-objidl-istorage-enumelements?branch=dev)
##### [MoveElementTo](/windows/win32/content/Objidl/nf-objidl-istorage-moveelementto?branch=dev)
##### [OpenStorage](/windows/win32/content/Objidl/nf-objidl-istorage-openstorage?branch=dev)
##### [OpenStream](/windows/win32/content/Objidl/nf-objidl-istorage-openstream?branch=dev)
##### [RemoteEnumElements](/windows/win32/content/Objidl/?branch=dev)
##### [RemoteOpenStream](/windows/win32/content/Objidl/?branch=dev)
##### [RenameElement](/windows/win32/content/Objidl/nf-objidl-istorage-renameelement?branch=dev)
##### [Revert](/windows/win32/content/Objidl/nf-objidl-istorage-revert?branch=dev)
##### [SetClass](/windows/win32/content/Objidl/nf-objidl-istorage-setclass?branch=dev)
##### [SetElementTimes](/windows/win32/content/Objidl/nf-objidl-istorage-setelementtimes?branch=dev)
##### [SetStateBits](/windows/win32/content/Objidl/nf-objidl-istorage-setstatebits?branch=dev)
##### [Stat](/windows/win32/content/Objidl/nf-objidl-istorage-stat?branch=dev)
##### [IStorage - Compound File Implementation](istorage-compound-file-implementation.md)
#### [IStream](/windows/win32/content/Objidl/nn-objidl-istream?branch=dev)
##### [Clone](/windows/win32/content/Objidl/nf-objidl-istream-clone?branch=dev)
##### [Commit](/windows/win32/content/Objidl/nf-objidl-istream-commit?branch=dev)
##### [CopyTo](/windows/win32/content/Objidl/nf-objidl-istream-copyto?branch=dev)
##### [LockRegion](/windows/win32/content/Objidl/nf-objidl-istream-lockregion?branch=dev)
##### [RemoteCopyTo](/windows/win32/content/Objidl/?branch=dev)
##### [RemoteSeek](/windows/win32/content/Objidl/?branch=dev)
##### [Revert](/windows/win32/content/Objidl/nf-objidl-istream-revert?branch=dev)
##### [Seek](/windows/win32/content/Objidl/nf-objidl-istream-seek?branch=dev)
##### [SetSize](/windows/win32/content/Objidl/nf-objidl-istream-setsize?branch=dev)
##### [Stat](/windows/win32/content/Objidl/nf-objidl-istream-stat?branch=dev)
##### [UnlockRegion](/windows/win32/content/Objidl/nf-objidl-istream-unlockregion?branch=dev)
##### [IStream - Compound File Implementation](istream-compound-file-implementation.md)
### [Functions](functions.md)
#### [CreateILockBytesOnHGlobal](/windows/win32/content/coml2api/nf-coml2api-createilockbytesonhglobal?branch=dev)
#### [CreateStreamOnHGlobal](/windows/win32/content/combaseapi/?branch=dev)
#### [FmtIdToPropStgName](/windows/win32/content/coml2api/nf-coml2api-fmtidtopropstgname?branch=dev)
#### [FreePropVariantArray](/windows/win32/content/Propidl/?branch=dev)
#### [GetConvertStg](/windows/win32/content/coml2api/nf-coml2api-getconvertstg?branch=dev)
#### [GetHGlobalFromILockBytes](/windows/win32/content/coml2api/nf-coml2api-gethglobalfromilockbytes?branch=dev)
#### [GetHGlobalFromStream](/windows/win32/content/combaseapi/?branch=dev)
#### [OleConvertIStorageToOLESTREAM](/windows/win32/content/Ole2/nf-ole2-oleconvertistoragetoolestream?branch=dev)
#### [OleConvertIStorageToOLESTREAMEx](/windows/win32/content/Ole2/nf-ole2-oleconvertistoragetoolestreamex?branch=dev)
#### [OleConvertOLESTREAMToIStorage](/windows/win32/content/Ole2/nf-ole2-oleconvertolestreamtoistorage?branch=dev)
#### [OleConvertOLESTREAMToIStorageEx](/windows/win32/content/Ole2/nf-ole2-oleconvertolestreamtoistorageex?branch=dev)
#### [PropStgNameToFmtId](/windows/win32/content/coml2api/nf-coml2api-propstgnametofmtid?branch=dev)
#### [PropVariantClear](/windows/win32/content/Propidl/?branch=dev)
#### [PropVariantCopy](/windows/win32/content/Propidl/?branch=dev)
#### [PropVariantInit](/windows/win32/content/PropIdl/nf-propidl-propvariantinit?branch=dev)
#### [ReadClassStg](/windows/win32/content/coml2api/nf-coml2api-readclassstg?branch=dev)
#### [ReadClassStm](/windows/win32/content/coml2api/nf-coml2api-readclassstm?branch=dev)
#### [ReadFmtUserTypeStg](/windows/win32/content/Ole2/nf-ole2-readfmtusertypestg?branch=dev)
#### [StgConvertPropertyToVariant](/windows/win32/content/Propidl/nf-propidl-stgconvertpropertytovariant?branch=dev)
#### [SetConvertStg](/windows/win32/content/Ole2/nf-ole2-setconvertstg?branch=dev)
#### [StgConvertVariantToProperty](/windows/win32/content/Propidl/nf-propidl-stgconvertvarianttoproperty?branch=dev)
#### [StgCreateDocfile](/windows/win32/content/coml2api/nf-coml2api-stgcreatedocfile?branch=dev)
#### [StgCreateDocfileOnILockBytes](/windows/win32/content/coml2api/nf-coml2api-stgcreatedocfileonilockbytes?branch=dev)
#### [StgCreatePropSetStg](/windows/win32/content/coml2api/nf-coml2api-stgcreatepropsetstg?branch=dev)
#### [StgCreatePropStg](/windows/win32/content/coml2api/nf-coml2api-stgcreatepropstg?branch=dev)
#### [StgCreateStorageEx](/windows/win32/content/coml2api/nf-coml2api-stgcreatestorageex?branch=dev)
#### [StgDeserializePropVariant](/windows/win32/content/Propvarutil/?branch=dev)
#### [StgGetIFillLockBytesOnFile](/windows/win32/content/Objbase/nf-objbase-stggetifilllockbytesonfile?branch=dev)
#### [StgGetIFillLockBytesOnILockBytes](/windows/win32/content/Objbase/nf-objbase-stggetifilllockbytesonilockbytes?branch=dev)
#### [StgIsStorageFile](/windows/win32/content/coml2api/nf-coml2api-stgisstoragefile?branch=dev)
#### [StgIsStorageILockBytes](/windows/win32/content/coml2api/nf-coml2api-stgisstorageilockbytes?branch=dev)
#### [StgOpenAsyncDocfileOnIFillLockBytes](/windows/win32/content/Objbase/nf-objbase-stgopenasyncdocfileonifilllockbytes?branch=dev)
#### [StgOpenLayoutDocfile](stgopenlayoutdocfile.md)
#### [StgOpenPropStg](/windows/win32/content/coml2api/nf-coml2api-stgopenpropstg?branch=dev)
#### [StgOpenStorage](/windows/win32/content/coml2api/nf-coml2api-stgopenstorage?branch=dev)
#### [StgOpenStorageEx](/windows/win32/content/coml2api/nf-coml2api-stgopenstorageex?branch=dev)
#### [StgOpenStorageOnILockBytes](/windows/win32/content/coml2api/nf-coml2api-stgopenstorageonilockbytes?branch=dev)
#### [StgPropertyLengthAsVariant](/windows/win32/content/Propapi/nf-propapi-stgpropertylengthasvariant?branch=dev)
#### [StgSetTimes](/windows/win32/content/coml2api/nf-coml2api-stgsettimes?branch=dev)
#### [StgSerializePropVariant](/windows/win32/content/Propvarutil/?branch=dev)
#### [WriteClassStg](/windows/win32/content/coml2api/nf-coml2api-writeclassstg?branch=dev)
#### [WriteClassStm](/windows/win32/content/coml2api/nf-coml2api-writeclassstm?branch=dev)
#### [WriteFmtUserTypeStg](/windows/win32/content/Ole2/nf-ole2-writefmtusertypestg?branch=dev)
### [Structures](structures.md)
#### [PROPSPEC](/windows/win32/content/propidlbase/ns-propidl-tagpropspec?branch=dev)
#### [PROPVARIANT](/windows/win32/content/propidlbase/ns-propidl-tagpropvariant?branch=dev)
#### [RemSNB](/windows/win32/content/Objidl/ns-objidl-tagremsnb?branch=dev)
#### [SNB](snb.md)
#### [STATPROPSETSTG](/windows/win32/content/propidlbase/ns-propidl-tagstatpropsetstg?branch=dev)
#### [STATPROPSTG](/windows/win32/content/propidlbase/ns-propidl-tagstatpropstg?branch=dev)
#### [STATSTG](/windows/win32/content/Objidl/ns-objidl-tagstatstg?branch=dev)
#### [STGOPTIONS](/windows/win32/content/coml2api/ns-coml2api-tagstgoptions?branch=dev)
#### [StorageLayout](/windows/win32/content/Objidl/ns-objidl-tagstoragelayout?branch=dev)
### [Enumerations](enumerations.md)
#### [LOCKTYPE](/windows/win32/content/Objidl/ne-objidl-taglocktype?branch=dev)
#### [STATFLAG](/windows/win32/content/WTypes/ne-wtypes-tagstatflag?branch=dev)
#### [STGC](/windows/win32/content/WTypes/ne-wtypes-tagstgc?branch=dev)
#### [STGFMT](/windows/win32/content/Objbase/?branch=dev)
#### [STGMOVE](/windows/win32/content/WTypes/ne-wtypes-tagstgmove?branch=dev)
#### [STGTY](/windows/win32/content/Objidl/ne-objidl-tagstgty?branch=dev)
#### [STREAM_SEEK](/windows/win32/content/Objidl/ne-objidl-tagstream_seek?branch=dev)
### [Constants](constants.md)
#### [PROPSETFLAG Constants](propsetflag-constants.md)
#### [STGM Constants](stgm-constants.md)
### [Samples](samples.md)
#### [WriteRead Sample](writeread-sample.md)
#### [EnumAll Sample](enumall-sample.md)
#### [StgCreatePropSetStg Sample](stgcreatepropsetstg-sample.md)
