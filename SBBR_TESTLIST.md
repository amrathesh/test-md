# SBBR SCT Test Checklist

- [x] **`GenericTest`**
  - [x] **`EFICompliantTest`**
    - [x] **`PlatformSpecificElements`**
    - [x] **`RequiredElements`**
  - [x] **`SbbrRequiredUefiProtocols`**
    - [x] **`MediaIoProtocols`**
  - [x] **`SbbrEfiSpecVerLvl`**
    - [x] **`TestEfiSpecVerLvl`**
  - [x] **`SbbrSysEnvConfig`**
    - [x] **`BootExcLevel`**
- [x] **`BootServicesTest`**
  - [x] **`EventTimerandPriorityServicesTest`**
    - [x] **`CheckEvent_Conf`**
    - [x] **`CheckEvent_Func`**
    - [x] **`CloseEvent_Func`**
    - [x] **`CreateEventEx_Conf`**
    - [x] **`CreateEventEx_Func`**
    - [x] **`CreateEvent_Conf`**
    - [x] **`CreateEvent_Func`**
    - [x] **`RaiseTPL_Func`**
    - [x] **`RestoreTPL_Func`**
    - [x] **`SetTimer_Conf`**
    - [x] **`SetTimer_Func`**
    - [x] **`SignalEvent_Func`**
    - [x] **`WaitForEvent_Conf`**
    - [x] **`WaitForEvent_Func`**
  - [x] **`MemoryAllocationServicesTest`**
    - [x] **`AllocatePages_Conf`**
    - [x] **`AllocatePages_Func`**
    - [x] **`AllocatePool_Conf`**
    - [x] **`AllocatePool_Func`**
    - [x] **`FreePages_Conf`**
    - [x] **`FreePages_Func`**
    - [x] **`GetMemoryMap_Conf`**
    - [x] **`GetMemoryMap_Func`**
  - [x] **`ProtocolHandlerServicesTest`**
    - [x] **`CloseProtocol_Conf`**
    - [x] **`CloseProtocol_Func`**
    - [x] **`ConnectController_Conf`**
    - [x] **`ConnectController_Func`**
    - [x] **`DisconnectController_Conf`**
    - [x] **`DisconnectController_Func`**
    - [x] **`HandleProtocol_Conf`**
    - [x] **`HandleProtocol_Func`**
    - [x] **`InstallMultipleProtocolInterfaces_Conf`**
    - [x] **`InstallMultipleProtocolInterfaces_Func`**
    - [x] **`InstallProtocolInterface_Conf`**
    - [x] **`InstallProtocolInterface_Func`**
    - [x] **`LocateDevicePath_Conf`**
    - [x] **`LocateDevicePath_Func`**
    - [x] **`LocateHandleBuffer_Conf`**
    - [x] **`LocateHandleBuffer_Func`**
    - [x] **`LocateHandle_Conf`**
    - [x] **`LocateHandle_Func`**
    - [x] **`LocateProtocol_Conf`**
    - [x] **`LocateProtocol_Func`**
    - [x] **`OpenProtocolInformation_Conf`**
    - [x] **`OpenProtocolInformation_Func`**
    - [x] **`OpenProtocol_Conf`**
    - [x] **`OpenProtocol_Func_1`**
    - [x] **`OpenProtocol_Func_2`**
    - [x] **`OpenProtocol_Func_3`**
    - [x] **`ProtocolsPerHandle_Conf`**
    - [x] **`ProtocolsPerHandle_Func`**
    - [x] **`RegisterProtocolNotify_Conf`**
    - [x] **`RegisterProtocolNotify_Func`**
    - [x] **`ReinstallProtocolInterface_Conf`**
    - [x] **`ReinstallProtocolInterface_Func`**
    - [x] **`UninstallMultipleProtocolInterfaces_Co`**
    - [x] **`UninstallMultipleProtocolInterfaces_Fu`**
    - [x] **`UninstallProtocolInterface_Conf`**
    - [x] **`UninstallProtocolInterface_Func`**
  - [x] **`ImageServicesTest`**
    - [x] **`ExitBootServices_Conf`**
    - [x] **`Exit_Conf`**
    - [x] **`Exit_Func`**
    - [x] **`LoadImage_Conf`**
    - [x] **`LoadImage_Func`**
    - [x] **`StartImage_Conf`**
    - [x] **`StartImage_Func`**
    - [x] **`UnloadImage_Conf`**
    - [x] **`UnloadImage_Func`**
  - [x] **`MiscBootServicesTest`**
    - [x] **`CalculateCrc32_Conf`**
    - [x] **`CalculateCrc32_Func`**
    - [x] **`CopyMem_Func`**
    - [x] **`GetNextMonotonicCount_Conf`**
    - [x] **`GetNextMonotonicCount_Func`**
    - [x] **`InstallConfigurationTable_Conf`**
    - [x] **`InstallConfigurationTable_Func`**
    - [x] **`SetMem_Func`**
    - [x] **`SetWatchdogTimer_Conf`**
    - [x] **`SetWatchdogTimer_Func`**
    - [x] **`Stall_Func`**
  - [x] **`SbbrBootServices`**
    - [x] **`AcpiTable`**
    - [x] **`MemoryMap`**
    - [x] **`SmbiosTable`**
- [x] `RuntimeServicesTest`
  - [ ] SecureBootTest
    - [ ] ImageLoading
    - [ ] VariableAttributes
    - [ ] VariableUpdates
  - [x] `VariableServicesTest`
    - [ ] AuthVar_Conf
    - [ ] AuthVar_Func
    - [x] **`GetNextVariableName_Conf`**
    - [x] **`GetNextVariableName_Func`**
    - [x] **`GetVariable_Conf`**
    - [x] **`GetVariable_Func`**
    - [x] **`HardwareErrorRecord_Conf`**
    - [x] **`HardwareErrorRecord_Func`**
    - [x] **`QueryVariableInfo_Conf`**
    - [x] **`QueryVariableInfo_Func`**
    - [x] **`SetVariable_Conf`**
    - [x] **`SetVariable_Func`**
  - [ ] BBSRVariableSizeTest
    - [ ] BBSRVariableSizeTest_func
  - [x] **`TimeServicesTest`**
    - [x] **`GetTime_Conf`**
    - [x] **`GetTime_Func`**
    - [x] **`GetWakeupTime_Conf`**
    - [x] **`GetWakeupTime_Func`**
    - [x] **`SetTime_Conf`**
    - [x] **`SetTime_Func`**
    - [x] **`SetWakeupTime_Conf`**
    - [x] **`SetWakeupTime_Func`**
  - [x] `MiscRuntimeServicesTest`
    - [x] **`QueryCapsuleCapabilities_Conf`**
    - [x] **`QueryCapsuleCapabilities_Func`**
    - [ ] ResetSystem_Func
    - [x] **`UpdateCapsule_Conf`**
  - [x] `SBBRRuntimeServicesTest`
    - [x] **`Non`**
    - [ ] ResetSystem
    - [x] **`Runtime`**
- [x] **`LoadedImageProtocolTest`**
  - [x] **`LoadedImageProtocolTest1`**
  - [x] **`LoadedImageProtocolTest2`**
- [x] **`DevicePathProcotols`**
  - [x] **`DevicePathProcotolTest`**
    - [x] **`PathNode_Conf`**
  - [x] **`DevicePathUtilitiesProcotolTest`**
    - [x] **`AppendDeviceNode_Conformance`**
    - [x] **`AppendDeviceNode_Functionality`**
    - [x] **`AppendDevicePathInstance_Conformance`**
    - [x] **`AppendDevicePathInstance_Functionality`**
    - [x] **`AppendDevicePath_Conformance`**
    - [x] **`AppendDevicePath_Functionality`**
    - [x] **`CreatDeviceNode_Functionality`**
    - [x] **`CreateDeviceNode_Conformance`**
    - [x] **`DuplicateDevicePath_Conformance`**
    - [x] **`DuplicateDevicePath_Functionality`**
    - [x] **`GetDevicePathSize_Conformance`**
    - [x] **`GetDevicePathSize_Functionality`**
    - [x] **`GetNextDevicePathInstance_Conformance`**
    - [x] **`GetNextDevicePathInstance_Functionalit`**
    - [x] **`IsDevicePathMultiInstance_Functionalit`**
  - [x] **`DevicePathToTextProcotolTest`**
    - [x] **`ConvertDeviceNodeToText_Conformance`**
    - [x] **`ConvertDeviceNodeToText_Coverage`**
    - [x] **`ConvertDeviceNodeToText_Functionality`**
    - [x] **`ConvertDevicePathToText_Conformance`**
    - [x] **`ConvertDevicePathToText_Functionality`**
  - [x] **`DevicePathFromTextProcotolTest`**
    - [x] **`ConvertTextToDeviceNode_Conformance`**
    - [x] **`ConvertTextToDeviceNode_Coverage`**
    - [x] **`ConvertTextToDeviceNode_Functionality`**
    - [x] **`ConvertTextToDevicePath_Conformance`**
    - [x] **`ConvertTextToDevicePath_Coverage`**
    - [x] **`ConvertTextToDevicePath_Functionality`**
- [x] **`ACPITableProtocolTest`**
  - [x] **`InstallAcpiTableConformance`**
  - [x] **`InstallAcpiTableFunction`**
  - [x] **`UninstallAcpiTableConformance`**
  - [x] **`UninstallAcpiTableFunction`**
- [x] `DriverModelTest`
  - [ ] PlatformDriverOverrideProtocolTest
    - [ ] DriverLoaded_Conf
    - [ ] DriverLoaded_Func
    - [ ] GetDriverPath_Conf
    - [ ] GetDriverPath_Func
    - [ ] GetDriver_Conf
    - [ ] GetDriver_Func
  - [ ] BusSpecificDriverOverrideProtocolTest
    - [ ] GetDriver_Conf
  - [ ] DriverDiagnostics2ProtocolTest
    - [ ] RunDiagnostics_Conf
    - [ ] RunDiagnostics_Func
  - [x] **`ComponentName2ProtocolTest`**
    - [x] **`GetControllerName_Conf`**
    - [x] **`GetControllerName_Func`**
    - [x] **`GetDriverName_Conf`**
    - [x] **`GetDriverName_Func`**
  - [x] **`AdapterInformationProtocolTest`**
    - [x] **`GetInformationConformance`**
    - [x] **`GetInformationFunction`**
    - [x] **`GetSupportedTypesConformance`**
    - [x] **`GetSupportedTypesFunction`**
    - [x] **`SetInformationConformance`**
    - [x] **`SetInformationFunction`**
  - [ ] PlatformToDriverConfigurationProtocolT
- [x] `ConsoleSupportTest`
  - [x] **`SimpleTextInputExProtocolTest`**
    - [x] **`ReadKeyStrokeExConformance`**
    - [x] **`ReadKeyStrokeExFunctionAuto`**
    - [x] **`RegisterKeyNotifyConformance`**
    - [x] **`ResetFunctionAuto`**
    - [x] **`SetStateConformance`**
    - [x] **`UnregisterKeyNotifyConformance`**
  - [x] **`SimpleInputProtocolTest`**
    - [x] **`Reset_Func`**
  - [x] **`SimpleOutputProtocolTest`**
    - [x] **`ClearScreen_Func`**
    - [x] **`EnableCursor_Func`**
    - [x] **`OutputString_Func`**
    - [x] **`QueryMode_Conf`**
    - [x] **`QueryMode_Func`**
    - [x] **`Reset_Func`**
    - [x] **`SetAttribute_Func`**
    - [x] **`SetCursorPosition_Conf`**
    - [x] **`SetCursorPosition_Func`**
    - [x] **`SetMode_Conf`**
    - [x] **`SetMode_Func`**
    - [x] **`TestString_Func`**
  - [ ] SimplePointerProtocolTest
    - [ ] GetState_Func
    - [ ] Reset_Func
  - [ ] SerialIOProtocolTest
    - [ ] GetControl_Func
    - [ ] Read_Conf
    - [ ] Read_Func
    - [ ] Reset_Func
    - [ ] SetAttributes_Conf
    - [ ] SetAttributes_Func
    - [ ] SetControl_Conf
    - [ ] SetControl_Func
    - [ ] Write_Func
  - [x] **`GraphicsOutputProtocolTest`**
    - [x] **`BltVideoBltBuffer_Func`**
    - [x] **`BltVideoFill_Func`**
    - [x] **`BltVideoToVideo_Func`**
    - [x] **`Blt_Conf`**
    - [x] **`QueryMode_Conf`**
    - [x] **`QueryMode_Func`**
    - [x] **`SetMode_Conf`**
    - [x] **`SetMode_Func`**
  - [ ] AbsolutePointerProtocolTest
    - [ ] GetState_Conf
    - [ ] GetState_Func
    - [ ] Reset_Func
- [ ] MediaAccessTest
  - [ ] SimpleFileSystemProtocolTest
    - [ ] Close_Func
    - [ ] Delete_Conf
    - [ ] Delete_Func
    - [ ] FlushEx_Conf
    - [ ] FlushEx_Func
    - [ ] Flush_Conf
    - [ ] Flush_Func
    - [ ] GetInfo_Conf
    - [ ] GetInfo_Func
    - [ ] GetPosition_Conf
    - [ ] GetPosition_Func
    - [ ] OpenEx_Conf
    - [ ] OpenEx_Func
    - [ ] OpenVolume_Func
    - [ ] Open_Conf
    - [ ] Open_Func
    - [ ] ReadEx_Conf
    - [ ] ReadEx_Func
    - [ ] Read_Func
    - [ ] SetInfo_Conf
    - [ ] SetInfo_Func
    - [ ] SetPosition_Conf
    - [ ] SetPosition_Func
    - [ ] WriteEx_Conf
    - [ ] WriteEx_Func
    - [ ] Write_Conf
    - [ ] Write_Func
  - [ ] DiskIOProtocolTest
    - [ ] ReadDisk_Conf
    - [ ] ReadDisk_Func
  - [ ] DiskIO2ProtocolTest
    - [ ] Cancel_Func
    - [ ] FlushDiskEx_Conf
    - [ ] FlushDiskEx_Func
    - [ ] ReadDiskEx_Conf
    - [ ] ReadDiskEx_Func
    - [ ] WriteDiskEx_Conf
    - [ ] WriteDiskEx_Func
  - [ ] BlockIOProtocolTest
    - [ ] FlushBlocks_Conf
    - [ ] FlushBlocks_Func
    - [ ] MediaInfo_Integrity
    - [ ] ReadBlocks_Conf
    - [ ] ReadBlocks_Func
    - [ ] Reset_Func
  - [ ] BlockIO2ProtocolTest
    - [ ] FlushBlocksEx_Conf
    - [ ] FlushBlocksEx_Func
    - [ ] MediaInfo_Integrity
    - [ ] ReadBlocksEx_Conf
    - [ ] ReadBlocksEx_Func
    - [ ] Reset_Func
    - [ ] WriteBlocksEx_Conf
    - [ ] WriteBlocksEx_Func
  - [ ] StorageSecurityCommandProtocolTest
    - [ ] ReceiveData_Conf
    - [ ] SendData_Conf
  - [ ] RamDiskProtocolTest
    - [ ] RegisterRamDiskConformance
    - [ ] RegisterRamDiskFunction
    - [ ] UnregisterRamDiskConformance
    - [ ] UnregisterRamDiskFunction
  - [ ] NVMEPassThruTest
    - [ ] BuildDevicePathConformance
    - [ ] BuildDevicePathFunction
    - [ ] GetNamespaceConformance
    - [ ] GetNamespaceFunction
    - [ ] GetNextNamespaceConformance
    - [ ] GetNextNamespaceFunction
    - [ ] PassThruConformance
    - [ ] PassThruFunction
  - [ ] EraseBlock
    - [ ] EraseBlocksConformance
    - [ ] EraseBlocksFunction
  - [ ] SdMmcPassThru
    - [ ] BuildDevicePathConformance
    - [ ] BuildDevicePathFunction
    - [ ] GetNextSlotConformance
    - [ ] GetNextSlotFunction
    - [ ] GetSlotNumberConformance
    - [ ] GetSlotNumberFunction
    - [ ] PassThruConformance
    - [ ] PassThruFunction
    - [ ] ResetDeviceConformance
    - [ ] ResetDeviceFunction
  - [ ] PartitionInfo
    - [ ] PartitionInfoFunction
  - [ ] UFSDeviceConfig
    - [ ] RwUfsAttributeConformance
    - [ ] RwUfsDescriptorConformance
    - [ ] RwUfsFlagConformance
  - [ ] ATAPassThruProtocolTest
    - [ ] BuildDevicePath_Conf
    - [ ] BuildDevicePath_Func
    - [ ] GetDevice_Conf
    - [ ] GetDevice_Func
    - [ ] GetNextDevice_Conf
    - [ ] GetNextDevice_Func
    - [ ] GetNextPort_Conf
    - [ ] GetNextPort_Func
    - [ ] Mode_Conf
    - [ ] PassThru_Conf
    - [ ] PassThru_Func
    - [ ] ResetDevice_Conf
    - [ ] ResetDevice_Func
    - [ ] ResetPort_Func
  - [ ] TapeIoProtocolTest
    - [ ] TapeTest_I
    - [ ] TapeTest_II
    - [ ] TapeTest_III
    - [ ] TapeTest_IV
    - [ ] TapeTest_V
    - [ ] TapeTest_VI
- [x] `StringServiceTest`
  - [x] **`UnicodeCollation2ProtocolTest`**
    - [x] **`FatToStr_Func`**
    - [x] **`MetaiMatch_Func`**
    - [x] **`StriColl_Func`**
    - [x] **`StrLwr_Func`**
    - [x] **`StrToFat_Func`**
    - [x] **`StrUpr_Func`**
  - [ ] RegularExpressionProtocolTest
    - [ ] GetInfo_Conf
    - [ ] GetInfo_Func
    - [ ] MatchString_Conf
    - [ ] MatchString_Func
- [x] **`PCIBusSupportTest`**
  - [x] **`PCIRootBridgeIOProtocolTest`**
    - [x] **`AllocateBuffer_Conf`**
    - [x] **`AllocateBuffer_Func`**
    - [x] **`Configuration_Func`**
    - [x] **`CopyMem_Conf`**
    - [x] **`CopyMem_Func`**
    - [x] **`Flush_Func`**
    - [x] **`FreeBuffer_Func`**
    - [x] **`GetAttributes_Conf`**
    - [x] **`GetAttributes_Func`**
    - [x] **`IoRead_Conf`**
    - [x] **`IoRead_Func`**
    - [x] **`IoWrite_Conf`**
    - [x] **`IoWrite_Func`**
    - [x] **`Map_Conf`**
    - [x] **`MemRead_Conf`**
    - [x] **`MemRead_Func`**
    - [x] **`MemWrite_Conf`**
    - [x] **`MemWrite_Func`**
    - [x] **`PciRead_Conf`**
    - [x] **`PciRead_Func`**
    - [x] **`PciWrite_Conf`**
    - [x] **`PciWrite_Func`**
    - [x] **`PollIo_Conf`**
    - [x] **`PollIo_Func`**
    - [x] **`PollMem_Conf`**
    - [x] **`PollMem_Func`**
    - [x] **`SetAttributes_Conf`**
    - [x] **`SetAttributes_Func`**
  - [x] **`PCIIOProtocolTest`**
    - [x] **`AllocateBuffer_Conf`**
    - [x] **`AllocateBuffer_Func`**
    - [x] **`Attributes_Conf`**
    - [x] **`CopyMem_Conf`**
    - [x] **`CopyMem_Func`**
    - [x] **`Flush_Func`**
    - [x] **`FreeBuffer_Func`**
    - [x] **`GetBarAttributes_Conf`**
    - [x] **`GetBarAttributes_Func`**
    - [x] **`GetLocation_Conf`**
    - [x] **`GetLocation_Func`**
    - [x] **`IoRead_Conf`**
    - [x] **`IoRead_Func`**
    - [x] **`IoWrite_Conf`**
    - [x] **`IoWrite_Func`**
    - [x] **`Map_Conf`**
    - [x] **`MemRead_Conf`**
    - [x] **`MemRead_Func`**
    - [x] **`MemWrite_Conf`**
    - [x] **`MemWrite_Func`**
    - [x] **`PciRead_Conf`**
    - [x] **`PciRead_Func`**
    - [x] **`PciWrite_Conf`**
    - [x] **`PciWrite_Func`**
    - [x] **`PollIo_Conf`**
    - [x] **`PollIo_Func`**
    - [x] **`PollMem_Conf`**
    - [x] **`PollMem_Func`**
    - [x] **`SetBarAttributes_Conf`**
    - [x] **`SetBarAttributes_Func`**
- [ ] SCSIBusSupportTest
  - [ ] SCSIIoProtocolTest
    - [ ] ExecuteScsiCommand_Conf
    - [ ] ExecuteScsiCommand_Func
    - [ ] GetDeviceLocation_Conf
    - [ ] GetDeviceLocation_Func
    - [ ] GetDeviceType_Conf
    - [ ] GetDeviceType_Func
    - [ ] ResetBus_Func
    - [ ] ResetDevice_Func
  - [ ] ExtendedSCSIPassThruProtocolTest
    - [ ] BuildDevicePath_Conf
    - [ ] BuildDevicePath_Func
    - [ ] GetNextTargetLun_Conf
    - [ ] GetNextTargetLun_Func
    - [ ] GetNextTarget_Conf
    - [ ] GetNextTarget_Func
    - [ ] GetTargetLun_Conf
    - [ ] GetTargetLun_Func
    - [ ] PassThru_Conf
    - [ ] PassThru_Func
    - [ ] ResetChannel_Func
    - [ ] ResetTargetLun_Conf
    - [ ] ResetTargetLun_Func
- [ ] ISCSIBootTest
  - [ ] ISCSIInitiatorNameProtocol
    - [ ] Get_Conf
    - [ ] Get_Func
    - [ ] Set_Conf
    - [ ] Set_Func
- [ ] USBSupportTest
  - [ ] USB2HostControllerProtocolTest
    - [ ] AsyncInterruptTransfer_Conf
    - [ ] AsyncIsochronousTransfer_Conf
    - [ ] BulkTransfer_Conf
    - [ ] ClearRootHubPortFeature_Conf
    - [ ] ControlTransfer_Conf_Auto
    - [ ] GetCapability_Conf
    - [ ] GetRootHubPortStatus_Conf
    - [ ] GetState_Conf
    - [ ] IsochronousTransfer_Conf
    - [ ] Reset_Conf
    - [ ] SetRootHubPortFeature_Conf
    - [ ] SetState_Conf
    - [ ] SyncInterruptTransfer_Conf
  - [ ] USBIOProtocolTest
    - [ ] UsbAsyncInterruptTransfer_Conf
    - [ ] UsbAsyncIsochronousTransfer_Conf
    - [ ] UsbBulkTransfer_Conf
    - [ ] UsbControlTransfer_Conf
    - [ ] UsbGetConfigDescriptor_Conf
    - [ ] UsbGetDeviceDescriptor_Conf
    - [ ] UsbGetEndpointDescriptor_Conf
    - [ ] UsbGetInterfaceDescriptor_Conf
    - [ ] UsbGetStringDescriptor_Conf
    - [ ] UsbIsochronousTransfer_Conf
    - [ ] UsbPortReset_Conf
    - [ ] UsbSyncInterruptTransfer_Conf
- [x] `NetworkSupportTest`
  - [x] `SimpleNetworkProtocolTest`
    - [x] **`GetStatus_Conf`**
    - [x] **`GetStatus_Func`**
    - [x] **`Initialize_Conf`**
    - [x] **`Initialize_Func`**
    - [x] **`MCastIpToMac_Conf`**
    - [x] **`MCastIpToMac_Func`**
    - [ ] NVData_Conf
    - [ ] NVData_Func
    - [ ] ReceiveFilter_Conf
    - [ ] ReceiveFilter_Func
    - [x] **`Receive_Conf`**
    - [x] **`Reset_Conf`**
    - [x] **`Reset_Func`**
    - [x] **`Shutdown_Conf`**
    - [x] **`Shutdown_Func`**
    - [x] **`Start_Conf`**
    - [x] **`Start_Func`**
    - [ ] StationAddress_Conf
    - [ ] StationAddress_Func
    - [ ] Statistics_Conf
    - [ ] Statistics_Func
    - [x] **`Stop_Conf`**
    - [x] **`Stop_Func`**
    - [x] **`Transmit_Conf`**
  - [x] **`PXEBaseCodeProtocolTest`**
    - [x] **`Arp_Conf`**
    - [x] **`SetIpFilter_Func`**
    - [x] **`Start_Conf`**
    - [x] **`Start_Func`**
    - [x] **`Stop_Conf`**
    - [x] **`Stop_Func`**
  - [ ] VLANConfigProtocolTest
    - [ ] FindConformance
    - [ ] FindFunction
    - [ ] RemoveConformance
    - [ ] RemoveFunction
    - [ ] SetConformance
    - [ ] SetFunction
  - [ ] IPsecConfigProtocolTest
    - [ ] GetDataConformance
    - [ ] GetDataFunction
    - [ ] GetNextSelectorConformance
    - [ ] GetNextSelectorFunction
    - [ ] RegisterDataNotifyConformance
    - [ ] RegisterDataNotifyFunction
    - [ ] SetDataConformance
    - [ ] SetDataFunction
    - [ ] UnregisterDataNotifyConformance
    - [ ] UnregisterDataNotifyFunction
  - [ ] IPsec2ProtocolTest
    - [ ] ProcessExtConformance
    - [ ] ProcessExtFunction
- [ ] DebuggerSupportTest
  - [ ] DebugSupportProtocolTest
    - [ ] GetMaximumProcessorIndex_Func
    - [ ] InvalidateInstructionCache_Func
    - [ ] Isa_Func
    - [ ] RegisterPeriodicCallback_Func
  - [ ] DebugPortProtocolTest
    - [ ] Reset_Func
- [ ] CompressionTest
  - [ ] DecompressProtocolTest
    - [ ] Decompress_Conf
    - [ ] Decompress_Func
    - [ ] GetInfo_Func
- [ ] EFIByteCodeTest
  - [ ] EBCInterpreterProtocolTest
    - [ ] GetVersion_Conf
    - [ ] GetVersion_Func
    - [ ] UnloadImage_Conf
- [ ] TimeStampProtocolTest
  - [ ] GetPropertiesConformanceAuto
  - [ ] GetPropertiesFunctionAuto
  - [ ] GetTimestampFunctionAuto
- [ ] ResetNotificationProtocolTest
  - [ ] RegisterResetNotifyConformance
  - [ ] RegisterResetNotifyFunction
  - [ ] UnregisterResetNotifyConformance
  - [ ] UnregisterResetNotifyFunction
- [x] `SecureTechTest`
  - [x] **`RNGProtocolTest`**
    - [x] **`GetInfo_Conf`**
    - [x] **`GetInfo_Func`**
    - [x] **`GetRNG_Conf`**
    - [x] **`GetRNG_Func`**
  - [x] **`Hash2Test`**
    - [x] **`GetHashSizeConformance`**
    - [x] **`GetHashSizeFunction`**
    - [x] **`HashConformance`**
    - [x] **`HashFinalConformance`**
    - [x] **`HashFunction`**
    - [x] **`HashInitConformance`**
    - [x] **`HashMultiBlocksFunction`**
    - [x] **`HashUpdateConformance`**
  - [ ] PKCS7VerifyTest
    - [ ] VerifyBufferConformance
    - [ ] VerifyBufferFunction
    - [ ] VerifySignatureConformance
    - [ ] VerifySignatureFunction
- [x] `HIITest`
  - [x] **`HIIDatabaseProtocolTest`**
    - [x] **`ExportPackageListsConformance`**
    - [x] **`ExportPackageListsFunction`**
    - [x] **`FindKeyboardLayoutsConformance`**
    - [x] **`FindKeyboardLayoutsFunction`**
    - [x] **`GetKeyboardLayoutConformance`**
    - [x] **`GetKeyboardLayoutFunction`**
    - [x] **`GetPackageListHandleConformance`**
    - [x] **`GetPackageListHandleFunction`**
    - [x] **`ListPackageListsConformance`**
    - [x] **`ListPackageListsFunction`**
    - [x] **`NewPackageListConformance`**
    - [x] **`NewPackageListFunction`**
    - [x] **`RegisterPackageNotifyConformance`**
    - [x] **`RemovePackageListConformance`**
    - [x] **`RemovePackageListFunction`**
    - [x] **`SetKeyboardLayoutConformance`**
    - [x] **`SetKeyboardLayoutFunction`**
    - [x] **`UnregisterPackageNotifyConformance`**
    - [x] **`UpdatePackageListConformance`**
    - [x] **`UpdatePackageListFunction`**
  - [x] **`HIIStringProtocolTest`**
    - [x] **`GetLanguagesConformance`**
    - [x] **`GetLanguagesFunction`**
    - [x] **`GetSecondaryLanguagesConformance`**
    - [x] **`GetSecondaryLanguagesFunction`**
    - [x] **`GetStringConformance`**
    - [x] **`GetStringFunction`**
    - [x] **`NewStringConformance`**
    - [x] **`NewStringFunction`**
    - [x] **`SetStringConformance`**
    - [x] **`SetStringFunction`**
  - [ ] HIIImageProtocolTest
    - [ ] DrawImageConformance
    - [ ] DrawImageFunction
    - [ ] DrawImageIdConformance
    - [ ] DrawImageIdFunction
    - [ ] GetImageConformance
    - [ ] GetImageFunction
    - [ ] NewImageConformance
    - [ ] NewImageFunction
    - [ ] SetImageConformance
    - [ ] SetImageFunction
  - [ ] HIIImageExProtocolTest
    - [ ] DrawImageExConformance
    - [ ] DrawImageExFunction
    - [ ] DrawImageIdExConformance
    - [ ] DrawImageIdExFunction
    - [ ] GetImageExConformance
    - [ ] GetImageExFunction
    - [ ] GetImageInfoConformance
    - [ ] GetImageInfoFunction
    - [ ] NewImageExConformance
    - [ ] NewImageExFunction
    - [ ] SetImageExConformance
    - [ ] SetImageExFunction
  - [ ] HIIFontProtocolTest
    - [ ] GetFontInfoConformance
    - [ ] GetFontInfoFunction
    - [ ] GetGlyphConformance
    - [ ] GetGlyphFunction
    - [ ] StringIdToImageConformance
    - [ ] StringIdToImageFunction
    - [ ] StringToImageConformance
    - [ ] StringToImageFunction
  - [ ] HIIFontExProtocolTest
    - [ ] GetFontInfoExConformance
    - [ ] GetFontInfoExFunction
    - [ ] GetGlyphExConformance
    - [ ] GetGlyphExFunction
    - [ ] GetGlyphInfoConformance
    - [ ] GetGlyphInfoFunction
    - [ ] StringIdToImageExConformance
    - [ ] StringIdToImageExFunction
    - [ ] StringToImageExConformance
    - [ ] StringToImageExFunction
  - [x] **`HIIConfigAccessProtocolTest`**
    - [x] **`ExtractConfigConformance`**
    - [x] **`ExtractConfigFunction`**
    - [x] **`RouteConfigConformance`**
    - [x] **`RouteConfigFunction`**
  - [x] **`HIIConfigRoutingProtocolTest`**
    - [x] **`BlockToConfig_Conf`**
    - [x] **`BlockToConfig_Func`**
    - [x] **`ConfigToBlock_Conf`**
    - [x] **`ConfigToBlock_Func`**
    - [x] **`ExportConfig_Conf`**
    - [x] **`ExportConfig_Func`**
    - [x] **`ExtractConfig_Conf`**
    - [x] **`ExtractConfig_Func`**
    - [x] **`GetAltCfg_Conf`**
    - [x] **`GetAltCfg_Func`**
    - [x] **`RouteConfig_Conf`**
    - [x] **`RouteConfig_Func`**
  - [ ] ConfigKeywordHandlerTest
    - [ ] GetDataConformance
    - [ ] GetDataFunction
    - [ ] SetDataConformance
    - [ ] SetDataFunction
- [x] **`FirmwareManagementTest`**
  - [x] **`FirmwareManagementProtocol`**
    - [x] **`Conformance_Test`**
    - [x] **`Function_Test`**
- [ ] TCG2ProtocolTest
  - [ ] GetActivePcrBanks_Conf
  - [ ] GetCapability_Conf
  - [ ] HashLogExtendEvent_Conf
  - [ ] SubmitCommand_Conf
