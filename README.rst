SBBR SCT TestCase Checklist
===========================

Legend: |Test_Enabled| |Test_Partially_Enabled| |Test_Disabled|

.. table::

  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  |Suite                                        |Subsuite/TestCase                            |TestCase                                     |
  +=============================================+=============================================+=============================================+
  | |GenericTest|                               | |EFICompliantTest|                          | |PlatformSpecificElements|                  |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |RequiredElements|                          |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |SbbrRequiredUefiProtocols|                 | |MediaIoProtocols|                          |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |SbbrEfiSpecVerLvl|                         | |TestEfiSpecVerLvl|                         |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |SbbrSysEnvConfig|                          | |BootExcLevel|                              |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |BootServicesTest|                          | |EventTimerandPriorityServicesTest|         | |CheckEvent_Conf|                           |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |CheckEvent_Func|                           |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |CloseEvent_Func|                           |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |CreateEventEx_Conf|                        |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |CreateEventEx_Func|                        |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |CreateEvent_Conf|                          |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |CreateEvent_Func|                          |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |RaiseTPL_Func|                             |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |RestoreTPL_Func|                           |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |SetTimer_Conf|                             |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |SetTimer_Func|                             |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |SignalEvent_Func|                          |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |WaitForEvent_Conf|                         |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |WaitForEvent_Func|                         |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |MemoryAllocationServicesTest|              | |AllocatePages_Conf|                        |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |AllocatePages_Func|                        |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |AllocatePool_Conf|                         |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |AllocatePool_Func|                         |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |FreePages_Conf|                            |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |FreePages_Func|                            |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |GetMemoryMap_Conf|                         |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |GetMemoryMap_Func|                         |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |ProtocolHandlerServicesTest|               | |CloseProtocol_Conf|                        |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |CloseProtocol_Func|                        |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |ConnectController_Conf|                    |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |ConnectController_Func|                    |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |DisconnectController_Conf|                 |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |DisconnectController_Func|                 |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |HandleProtocol_Conf|                       |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |HandleProtocol_Func|                       |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |InstallMultipleProtocolInterfaces_Conf|    |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |InstallMultipleProtocolInterfaces_Func|    |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |InstallProtocolInterface_Conf|             |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |InstallProtocolInterface_Func|             |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateDevicePath_Conf|                     |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateDevicePath_Func|                     |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateHandleBuffer_Conf|                   |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateHandleBuffer_Func|                   |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateHandle_Conf|                         |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateHandle_Func|                         |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateProtocol_Conf|                       |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |LocateProtocol_Func|                       |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |OpenProtocolInformation_Conf|              |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |OpenProtocolInformation_Func|              |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |OpenProtocol_Conf|                         |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |OpenProtocol_Func_1|                       |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |OpenProtocol_Func_2|                       |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |OpenProtocol_Func_3|                       |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |ProtocolsPerHandle_Conf|                   |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |ProtocolsPerHandle_Func|                   |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |RegisterProtocolNotify_Conf|               |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |RegisterProtocolNotify_Func|               |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |ReinstallProtocolInterface_Conf|           |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |ReinstallProtocolInterface_Func|           |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |UninstallMultipleProtocolInterfaces_Co|    |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |UninstallMultipleProtocolInterfaces_Fu|    |
  |                                             |                                             +---------------------------------------------+
  |                                             |                                             | |UninstallProtocolInterface_Func|           |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |ImageServicesTest|                         |                                             |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |MiscBootServicesTest|                      |                                             |
  |                                             +---------------------------------------------+---------------------------------------------+
  |                                             | |SbbrBootServices|                          |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |RuntimeServicesTest|                       |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |LoadedImageProtocolTest|                   |                                             |                                             | 
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |DevicePathProcotols|                       |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |GenericTest|                               |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |ACPITableProtocolTest|                     |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |DriverModelTest|                           |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |ConsoleSupportTest|                        |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |MediaAccessTest|                           |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |StringServiceTest|                         |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |PCIBusSupportTest|                         |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |SCSIBusSupportTest|                        |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |ISCSIBootTest|                             |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |USBSupportTest|                            |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |NetworkSupportTest|                        |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |DebuggerSupportTest|                       |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |CompressionTest|                           |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |EFIByteCodeTest|                           |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |TimeStampProtocolTest|                     |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |ResetNotificationProtocolTest|             |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |SecureTechTest|                            |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |HIITest|                                   |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |FirmwareManagementTest|                    |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+
  | |TCG2ProtocolTest|                          |                                             |                                             |
  +---------------------------------------------+---------------------------------------------+---------------------------------------------+



..
  All alias directives here

.. |Test_Enabled| image:: https://img.shields.io/badge/Test_Enabled-darkgreen
  :height: 20
.. |Test_Partially_Enabled| image:: https://img.shields.io/badge/Test_Partially_Enabled-orange
  :height: 20
.. |Test_Disabled| image:: https://img.shields.io/badge/Test_Disabled-gray
  :height: 20


.. |RuntimeServicesTest| image:: https://img.shields.io/badge/RuntimeServicesTest-orange
  :height: 25
.. |DriverModelTest| image:: https://img.shields.io/badge/DriverModelTest-orange
  :height: 25
.. |ConsoleSupportTest| image:: https://img.shields.io/badge/ConsoleSupportTest-orange
  :height: 25
.. |StringServiceTest| image:: https://img.shields.io/badge/StringServiceTest-orange
  :height: 25
.. |NetworkSupportTest| image:: https://img.shields.io/badge/NetworkSupportTest-orange
  :height: 25
.. |SecureTechTest| image:: https://img.shields.io/badge/SecureTechTest-orange
  :height: 25
.. |HIITest| image:: https://img.shields.io/badge/HIITest-orange
  :height: 25
.. |VariableServicesTest| image:: https://img.shields.io/badge/VariableServicesTest-orange
  :height: 25
.. |MiscRuntimeServicesTest| image:: https://img.shields.io/badge/MiscRuntimeServicesTest-orange
  :height: 25
.. |SBBRRuntimeServicesTest| image:: https://img.shields.io/badge/SBBRRuntimeServicesTest-orange
  :height: 25

.. |GenericTest| image:: https://img.shields.io/badge/GenericTest-darkgreen
  :height: 25
.. |BootServicesTest| image:: https://img.shields.io/badge/BootServicesTest-darkgreen
  :height: 25
.. |LoadedImageProtocolTest| image:: https://img.shields.io/badge/LoadedImageProtocolTest-darkgreen
  :height: 25
.. |DevicePathProcotols| image:: https://img.shields.io/badge/DevicePathProcotols-darkgreen
  :height: 25
.. |ACPITableProtocolTest| image:: https://img.shields.io/badge/ACPITableProtocolTest-darkgreen
  :height: 25
.. |PCIBusSupportTest| image:: https://img.shields.io/badge/PCIBusSupportTest-darkgreen
  :height: 25
.. |FirmwareManagementTest| image:: https://img.shields.io/badge/FirmwareManagementTest-darkgreen
  :height: 25
.. |EFICompliantTest| image:: https://img.shields.io/badge/EFICompliantTest-darkgreen
  :height: 25
.. |SbbrRequiredUefiProtocols| image:: https://img.shields.io/badge/SbbrRequiredUefiProtocols-darkgreen
  :height: 25
.. |SbbrEfiSpecVerLvl| image:: https://img.shields.io/badge/SbbrEfiSpecVerLvl-darkgreen
  :height: 25
.. |SbbrSysEnvConfig| image:: https://img.shields.io/badge/SbbrSysEnvConfig-darkgreen
  :height: 25
.. |PlatformSpecificElements| image:: https://img.shields.io/badge/PlatformSpecificElements-darkgreen
  :height: 25
.. |RequiredElements| image:: https://img.shields.io/badge/RequiredElements-darkgreen
  :height: 25
.. |MediaIoProtocols| image:: https://img.shields.io/badge/MediaIoProtocols-darkgreen
  :height: 25
.. |TestEfiSpecVerLvl| image:: https://img.shields.io/badge/TestEfiSpecVerLvl-darkgreen
  :height: 25
.. |TestEfiSpecVerLvl| image:: https://img.shields.io/badge/TestEfiSpecVerLvl-darkgreen
  :height: 25
.. |BootExcLevel| image:: https://img.shields.io/badge/BootExcLevel-darkgreen
  :height: 25
.. |EventTimerandPriorityServicesTest| image:: https://img.shields.io/badge/EventTimerandPriorityServicesTest-darkgreen
  :height: 25
.. |MemoryAllocationServicesTest| image:: https://img.shields.io/badge/MemoryAllocationServicesTest-darkgreen
  :height: 25
.. |ProtocolHandlerServicesTest| image:: https://img.shields.io/badge/ProtocolHandlerServicesTest-darkgreen
  :height: 25
.. |ImageServicesTest| image:: https://img.shields.io/badge/ImageServicesTest-darkgreen
  :height: 25
.. |MiscBootServicesTest| image:: https://img.shields.io/badge/MiscBootServicesTest-darkgreen
  :height: 25
.. |SbbrBootServices| image:: https://img.shields.io/badge/SbbrBootServices-darkgreen
  :height: 25
.. |CheckEvent_Conf| image:: https://img.shields.io/badge/CheckEvent_Conf-darkgreen
  :height: 25
.. |CheckEvent_Func| image:: https://img.shields.io/badge/CheckEvent_Func-darkgreen
  :height: 25
.. |CloseEvent_Func| image:: https://img.shields.io/badge/CloseEvent_Func-darkgreen
  :height: 25
.. |CreateEventEx_Conf| image:: https://img.shields.io/badge/CreateEventEx_Conf-darkgreen
  :height: 25
.. |CreateEventEx_Func| image:: https://img.shields.io/badge/CreateEventEx_Func-darkgreen
  :height: 25
.. |CreateEvent_Conf| image:: https://img.shields.io/badge/CreateEvent_Conf-darkgreen
  :height: 25
.. |CreateEvent_Func| image:: https://img.shields.io/badge/CreateEvent_Func-darkgreen
  :height: 25
.. |RaiseTPL_Func| image:: https://img.shields.io/badge/RaiseTPL_Func-darkgreen
  :height: 25
.. |RestoreTPL_Func| image:: https://img.shields.io/badge/RestoreTPL_Func-darkgreen
  :height: 25
.. |SetTimer_Conf| image:: https://img.shields.io/badge/SetTimer_Conf-darkgreen
  :height: 25
.. |SetTimer_Func| image:: https://img.shields.io/badge/SetTimer_Func-darkgreen
  :height: 25
.. |SignalEvent_Func| image:: https://img.shields.io/badge/SignalEvent_Func-darkgreen
  :height: 25
.. |WaitForEvent_Conf| image:: https://img.shields.io/badge/WaitForEvent_Conf-darkgreen
  :height: 25
.. |WaitForEvent_Func| image:: https://img.shields.io/badge/WaitForEvent_Func-darkgreen
  :height: 25
.. |AllocatePages_Conf| image:: https://img.shields.io/badge/AllocatePages_Conf-darkgreen
  :height: 25
.. |AllocatePages_Func| image:: https://img.shields.io/badge/AllocatePages_Func-darkgreen
  :height: 25
.. |AllocatePool_Conf| image:: https://img.shields.io/badge/AllocatePool_Conf-darkgreen
  :height: 25
.. |AllocatePool_Func| image:: https://img.shields.io/badge/AllocatePool_Func-darkgreen
  :height: 25
.. |FreePages_Conf| image:: https://img.shields.io/badge/FreePages_Conf-darkgreen
  :height: 25
.. |FreePages_Func| image:: https://img.shields.io/badge/FreePages_Func-darkgreen
  :height: 25
.. |GetMemoryMap_Conf| image:: https://img.shields.io/badge/GetMemoryMap_Conf-darkgreen
  :height: 25
.. |GetMemoryMap_Func| image:: https://img.shields.io/badge/GetMemoryMap_Func-darkgreen
  :height: 25
.. |CloseProtocol_Conf| image:: https://img.shields.io/badge/CloseProtocol_Conf-darkgreen
  :height: 25
.. |CloseProtocol_Func| image:: https://img.shields.io/badge/CloseProtocol_Func-darkgreen
  :height: 25
.. |ConnectController_Conf| image:: https://img.shields.io/badge/ConnectController_Conf-darkgreen
  :height: 25
.. |ConnectController_Func| image:: https://img.shields.io/badge/ConnectController_Func-darkgreen
  :height: 25
.. |DisconnectController_Conf| image:: https://img.shields.io/badge/DisconnectController_Conf-darkgreen
  :height: 25
.. |DisconnectController_Func| image:: https://img.shields.io/badge/DisconnectController_Func-darkgreen
  :height: 25
.. |HandleProtocol_Conf| image:: https://img.shields.io/badge/HandleProtocol_Conf-darkgreen
  :height: 25
.. |HandleProtocol_Func| image:: https://img.shields.io/badge/HandleProtocol_Func-darkgreen
  :height: 25
.. |InstallMultipleProtocolInterfaces_Conf| image:: https://img.shields.io/badge/InstallMultipleProtocolInterfaces_Conf-darkgreen
  :height: 25
.. |InstallMultipleProtocolInterfaces_Func| image:: https://img.shields.io/badge/InstallMultipleProtocolInterfaces_Func-darkgreen
  :height: 25
.. |InstallProtocolInterface_Conf| image:: https://img.shields.io/badge/InstallProtocolInterface_Conf-darkgreen
  :height: 25
.. |InstallProtocolInterface_Func| image:: https://img.shields.io/badge/InstallProtocolInterface_Func-darkgreen
  :height: 25
.. |LocateDevicePath_Conf| image:: https://img.shields.io/badge/LocateDevicePath_Conf-darkgreen
  :height: 25
.. |LocateDevicePath_Func| image:: https://img.shields.io/badge/LocateDevicePath_Func-darkgreen
  :height: 25
.. |LocateHandleBuffer_Conf| image:: https://img.shields.io/badge/LocateHandleBuffer_Conf-darkgreen
  :height: 25
.. |LocateHandleBuffer_Func| image:: https://img.shields.io/badge/LocateHandleBuffer_Func-darkgreen
  :height: 25
.. |LocateHandle_Conf| image:: https://img.shields.io/badge/LocateHandle_Conf-darkgreen
  :height: 25
.. |LocateHandle_Func| image:: https://img.shields.io/badge/LocateHandle_Func-darkgreen
  :height: 25
.. |LocateProtocol_Conf| image:: https://img.shields.io/badge/LocateProtocol_Conf-darkgreen
  :height: 25
.. |LocateProtocol_Func| image:: https://img.shields.io/badge/LocateProtocol_Func-darkgreen
  :height: 25
.. |OpenProtocolInformation_Conf| image:: https://img.shields.io/badge/OpenProtocolInformation_Conf-darkgreen
  :height: 25
.. |OpenProtocolInformation_Func| image:: https://img.shields.io/badge/OpenProtocolInformation_Func-darkgreen
  :height: 25
.. |OpenProtocol_Conf| image:: https://img.shields.io/badge/OpenProtocol_Conf-darkgreen
  :height: 25
.. |OpenProtocol_Func_1| image:: https://img.shields.io/badge/OpenProtocol_Func_1-darkgreen
  :height: 25
.. |OpenProtocol_Func_2| image:: https://img.shields.io/badge/OpenProtocol_Func_2-darkgreen
  :height: 25
.. |OpenProtocol_Func_3| image:: https://img.shields.io/badge/OpenProtocol_Func_3-darkgreen
  :height: 25
.. |ProtocolsPerHandle_Conf| image:: https://img.shields.io/badge/ProtocolsPerHandle_Conf-darkgreen
  :height: 25
.. |ProtocolsPerHandle_Func| image:: https://img.shields.io/badge/ProtocolsPerHandle_Func-darkgreen
  :height: 25
.. |RegisterProtocolNotify_Conf| image:: https://img.shields.io/badge/RegisterProtocolNotify_Conf-darkgreen
  :height: 25
.. |RegisterProtocolNotify_Func| image:: https://img.shields.io/badge/RegisterProtocolNotify_Func-darkgreen
  :height: 25
.. |ReinstallProtocolInterface_Conf| image:: https://img.shields.io/badge/ReinstallProtocolInterface_Conf-darkgreen
  :height: 25
.. |ReinstallProtocolInterface_Func| image:: https://img.shields.io/badge/ReinstallProtocolInterface_Func-darkgreen
  :height: 25
.. |UninstallMultipleProtocolInterfaces_Co| image:: https://img.shields.io/badge/UninstallMultipleProtocolInterfaces_Co-darkgreen
  :height: 25
.. |UninstallMultipleProtocolInterfaces_Fu| image:: https://img.shields.io/badge/UninstallMultipleProtocolInterfaces_Fu-darkgreen
  :height: 25
.. |UninstallProtocolInterface_Conf| image:: https://img.shields.io/badge/UninstallProtocolInterface_Conf-darkgreen
  :height: 25
.. |ExitBootServices_Conf| image:: https://img.shields.io/badge/ExitBootServices_Conf-darkgreen
  :height: 25
.. |Exit_Conf| image:: https://img.shields.io/badge/Exit_Conf-darkgreen
  :height: 25
.. |Exit_Func| image:: https://img.shields.io/badge/Exit_Func-darkgreen
  :height: 25
.. |LoadImage_Conf| image:: https://img.shields.io/badge/LoadImage_Conf-darkgreen
  :height: 25
.. |LoadImage_Func| image:: https://img.shields.io/badge/LoadImage_Func-darkgreen
  :height: 25
.. |StartImage_Conf| image:: https://img.shields.io/badge/StartImage_Conf-darkgreen
  :height: 25
.. |StartImage_Func| image:: https://img.shields.io/badge/StartImage_Func-darkgreen
  :height: 25
.. |UnloadImage_Conf| image:: https://img.shields.io/badge/UnloadImage_Conf-darkgreen
  :height: 25
.. |UnloadImage_Func| image:: https://img.shields.io/badge/UnloadImage_Func-darkgreen
  :height: 25
.. |CalculateCrc32_Conf| image:: https://img.shields.io/badge/CalculateCrc32_Conf-darkgreen
  :height: 25
.. |CalculateCrc32_Func| image:: https://img.shields.io/badge/CalculateCrc32_Func-darkgreen
  :height: 25
.. |CopyMem_Func| image:: https://img.shields.io/badge/CopyMem_Func-darkgreen
  :height: 25
.. |GetNextMonotonicCount_Conf| image:: https://img.shields.io/badge/GetNextMonotonicCount_Conf-darkgreen
  :height: 25
.. |GetNextMonotonicCount_Func| image:: https://img.shields.io/badge/GetNextMonotonicCount_Func-darkgreen
  :height: 25
.. |InstallConfigurationTable_Conf| image:: https://img.shields.io/badge/InstallConfigurationTable_Conf-darkgreen
  :height: 25
.. |InstallConfigurationTable_Func| image:: https://img.shields.io/badge/InstallConfigurationTable_Func-darkgreen
  :height: 25
.. |SetMem_Func| image:: https://img.shields.io/badge/SetMem_Func-darkgreen
  :height: 25
.. |SetWatchdogTimer_Conf| image:: https://img.shields.io/badge/SetWatchdogTimer_Conf-darkgreen
  :height: 25
.. |SetWatchdogTimer_Func| image:: https://img.shields.io/badge/SetWatchdogTimer_Func-darkgreen
  :height: 25
.. |Stall_Func| image:: https://img.shields.io/badge/Stall_Func-darkgreen
  :height: 25
.. |AcpiTable| image:: https://img.shields.io/badge/AcpiTable-darkgreen
  :height: 25
.. |MemoryMap| image:: https://img.shields.io/badge/MemoryMap-darkgreen
  :height: 25
.. |SmbiosTable| image:: https://img.shields.io/badge/SmbiosTable-darkgreen
  :height: 25
.. |TimeServicesTest| image:: https://img.shields.io/badge/TimeServicesTest-darkgreen
  :height: 25
.. |GetNextVariableName_Conf| image:: https://img.shields.io/badge/GetNextVariableName_Conf-darkgreen
  :height: 25
.. |GetNextVariableName_Func| image:: https://img.shields.io/badge/GetNextVariableName_Func-darkgreen
  :height: 25
.. |GetVariable_Conf| image:: https://img.shields.io/badge/GetVariable_Conf-darkgreen
  :height: 25
.. |GetVariable_Func| image:: https://img.shields.io/badge/GetVariable_Func-darkgreen
  :height: 25
.. |HardwareErrorRecord_Conf| image:: https://img.shields.io/badge/HardwareErrorRecord_Conf-darkgreen
  :height: 25
.. |HardwareErrorRecord_Func| image:: https://img.shields.io/badge/HardwareErrorRecord_Func-darkgreen
  :height: 25
.. |QueryVariableInfo_Conf| image:: https://img.shields.io/badge/QueryVariableInfo_Conf-darkgreen
  :height: 25
.. |QueryVariableInfo_Func| image:: https://img.shields.io/badge/QueryVariableInfo_Func-darkgreen
  :height: 25
.. |SetVariable_Conf| image:: https://img.shields.io/badge/SetVariable_Conf-darkgreen
  :height: 25
.. |SetVariable_Func| image:: https://img.shields.io/badge/SetVariable_Func-darkgreen
  :height: 25
.. |GetTime_Conf| image:: https://img.shields.io/badge/GetTime_Conf-darkgreen
  :height: 25
.. |GetTime_Func| image:: https://img.shields.io/badge/GetTime_Func-darkgreen
  :height: 25
.. |GetWakeupTime_Conf| image:: https://img.shields.io/badge/GetWakeupTime_Conf-darkgreen
  :height: 25
.. |GetWakeupTime_Func| image:: https://img.shields.io/badge/GetWakeupTime_Func-darkgreen
  :height: 25
.. |SetTime_Conf| image:: https://img.shields.io/badge/SetTime_Conf-darkgreen
  :height: 25
.. |SetTime_Func| image:: https://img.shields.io/badge/SetTime_Func-darkgreen
  :height: 25
.. |SetWakeupTime_Conf| image:: https://img.shields.io/badge/SetWakeupTime_Conf-darkgreen
  :height: 25
.. |SetWakeupTime_Func| image:: https://img.shields.io/badge/SetWakeupTime_Func-darkgreen
  :height: 25
.. |QueryCapsuleCapabilities_Conf| image:: https://img.shields.io/badge/QueryCapsuleCapabilities_Conf-darkgreen
  :height: 25
.. |QueryCapsuleCapabilities_Func| image:: https://img.shields.io/badge/QueryCapsuleCapabilities_Func-darkgreen
  :height: 25
.. |UpdateCapsule_Conf| image:: https://img.shields.io/badge/UpdateCapsule_Conf-darkgreen
  :height: 25
.. |Non| image:: https://img.shields.io/badge/Non-darkgreen
  :height: 25
.. |Runtime| image:: https://img.shields.io/badge/Runtime-darkgreen
  :height: 25
.. |LoadedImageProtocolTest1| image:: https://img.shields.io/badge/LoadedImageProtocolTest1-darkgreen
  :height: 25
.. |LoadedImageProtocolTest2| image:: https://img.shields.io/badge/LoadedImageProtocolTest2-darkgreen
  :height: 25
.. |DevicePathProcotolTest| image:: https://img.shields.io/badge/DevicePathProcotolTest-darkgreen
  :height: 25
.. |DevicePathUtilitiesProcotolTest| image:: https://img.shields.io/badge/DevicePathUtilitiesProcotolTest-darkgreen
  :height: 25
.. |DevicePathToTextProcotolTest| image:: https://img.shields.io/badge/DevicePathToTextProcotolTest-darkgreen
  :height: 25
.. |DevicePathFromTextProcotolTest| image:: https://img.shields.io/badge/DevicePathFromTextProcotolTest-darkgreen
  :height: 25
.. |PathNode_Conf| image:: https://img.shields.io/badge/PathNode_Conf-darkgreen
  :height: 25
.. |AppendDeviceNode_Conformance| image:: https://img.shields.io/badge/AppendDeviceNode_Conformance-darkgreen
  :height: 25
.. |AppendDeviceNode_Functionality| image:: https://img.shields.io/badge/AppendDeviceNode_Functionality-darkgreen
  :height: 25
.. |AppendDevicePathInstance_Conformance| image:: https://img.shields.io/badge/AppendDevicePathInstance_Conformance-darkgreen
  :height: 25
.. |AppendDevicePathInstance_Functionality| image:: https://img.shields.io/badge/AppendDevicePathInstance_Functionality-darkgreen
  :height: 25
.. |AppendDevicePath_Conformance| image:: https://img.shields.io/badge/AppendDevicePath_Conformance-darkgreen
  :height: 25
.. |AppendDevicePath_Functionality| image:: https://img.shields.io/badge/AppendDevicePath_Functionality-darkgreen
  :height: 25
.. |CreatDeviceNode_Functionality| image:: https://img.shields.io/badge/CreatDeviceNode_Functionality-darkgreen
  :height: 25
.. |CreateDeviceNode_Conformance| image:: https://img.shields.io/badge/CreateDeviceNode_Conformance-darkgreen
  :height: 25
.. |DuplicateDevicePath_Conformance| image:: https://img.shields.io/badge/DuplicateDevicePath_Conformance-darkgreen
  :height: 25
.. |DuplicateDevicePath_Functionality| image:: https://img.shields.io/badge/DuplicateDevicePath_Functionality-darkgreen
  :height: 25
.. |GetDevicePathSize_Conformance| image:: https://img.shields.io/badge/GetDevicePathSize_Conformance-darkgreen
  :height: 25
.. |GetDevicePathSize_Functionality| image:: https://img.shields.io/badge/GetDevicePathSize_Functionality-darkgreen
  :height: 25
.. |GetNextDevicePathInstance_Conformance| image:: https://img.shields.io/badge/GetNextDevicePathInstance_Conformance-darkgreen
  :height: 25
.. |GetNextDevicePathInstance_Functionalit| image:: https://img.shields.io/badge/GetNextDevicePathInstance_Functionalit-darkgreen
  :height: 25
.. |IsDevicePathMultiInstance_Functionalit| image:: https://img.shields.io/badge/IsDevicePathMultiInstance_Functionalit-darkgreen
  :height: 25
.. |ConvertDeviceNodeToText_Conformance| image:: https://img.shields.io/badge/ConvertDeviceNodeToText_Conformance-darkgreen
  :height: 25
.. |ConvertDeviceNodeToText_Coverage| image:: https://img.shields.io/badge/ConvertDeviceNodeToText_Coverage-darkgreen
  :height: 25
.. |ConvertDeviceNodeToText_Functionality| image:: https://img.shields.io/badge/ConvertDeviceNodeToText_Functionality-darkgreen
  :height: 25
.. |ConvertDevicePathToText_Conformance| image:: https://img.shields.io/badge/ConvertDevicePathToText_Conformance-darkgreen
  :height: 25
.. |ConvertDevicePathToText_Functionality| image:: https://img.shields.io/badge/ConvertDevicePathToText_Functionality-darkgreen
  :height: 25
.. |ConvertTextToDeviceNode_Conformance| image:: https://img.shields.io/badge/ConvertTextToDeviceNode_Conformance-darkgreen
  :height: 25
.. |ConvertTextToDeviceNode_Coverage| image:: https://img.shields.io/badge/ConvertTextToDeviceNode_Coverage-darkgreen
  :height: 25
.. |ConvertTextToDeviceNode_Functionality| image:: https://img.shields.io/badge/ConvertTextToDeviceNode_Functionality-darkgreen
  :height: 25
.. |ConvertTextToDevicePath_Conformance| image:: https://img.shields.io/badge/ConvertTextToDevicePath_Conformance-darkgreen
  :height: 25
.. |ConvertTextToDevicePath_Coverage| image:: https://img.shields.io/badge/ConvertTextToDevicePath_Coverage-darkgreen
  :height: 25
.. |ConvertTextToDevicePath_Functionality| image:: https://img.shields.io/badge/ConvertTextToDevicePath_Functionality-darkgreen
  :height: 25
.. |InstallAcpiTableConformance| image:: https://img.shields.io/badge/InstallAcpiTableConformance-darkgreen
  :height: 25
.. |InstallAcpiTableFunction| image:: https://img.shields.io/badge/InstallAcpiTableFunction-darkgreen
  :height: 25
.. |UninstallAcpiTableConformance| image:: https://img.shields.io/badge/UninstallAcpiTableConformance-darkgreen
  :height: 25
.. |UninstallAcpiTableFunction| image:: https://img.shields.io/badge/UninstallAcpiTableFunction-darkgreen
  :height: 25
.. |ComponentName2ProtocolTest| image:: https://img.shields.io/badge/ComponentName2ProtocolTest-darkgreen
  :height: 25
.. |AdapterInformationProtocolTest| image:: https://img.shields.io/badge/AdapterInformationProtocolTest-darkgreen
  :height: 25
.. |GetControllerName_Conf| image:: https://img.shields.io/badge/GetControllerName_Conf-darkgreen
  :height: 25
.. |GetControllerName_Func| image:: https://img.shields.io/badge/GetControllerName_Func-darkgreen
  :height: 25
.. |GetDriverName_Conf| image:: https://img.shields.io/badge/GetDriverName_Conf-darkgreen
  :height: 25
.. |GetDriverName_Func| image:: https://img.shields.io/badge/GetDriverName_Func-darkgreen
  :height: 25
.. |GetInformationConformance| image:: https://img.shields.io/badge/GetInformationConformance-darkgreen
  :height: 25
.. |GetInformationFunction| image:: https://img.shields.io/badge/GetInformationFunction-darkgreen
  :height: 25
.. |GetSupportedTypesConformance| image:: https://img.shields.io/badge/GetSupportedTypesConformance-darkgreen
  :height: 25
.. |GetSupportedTypesFunction| image:: https://img.shields.io/badge/GetSupportedTypesFunction-darkgreen
  :height: 25
.. |SetInformationConformance| image:: https://img.shields.io/badge/SetInformationConformance-darkgreen
  :height: 25
.. |SetInformationFunction| image:: https://img.shields.io/badge/SetInformationFunction-darkgreen
  :height: 25
.. |SimpleTextInputExProtocolTest| image:: https://img.shields.io/badge/SimpleTextInputExProtocolTest-darkgreen
  :height: 25
.. |SimpleInputProtocolTest| image:: https://img.shields.io/badge/SimpleInputProtocolTest-darkgreen
  :height: 25
.. |SimpleOutputProtocolTest| image:: https://img.shields.io/badge/SimpleOutputProtocolTest-darkgreen
  :height: 25
.. |GraphicsOutputProtocolTest| image:: https://img.shields.io/badge/GraphicsOutputProtocolTest-darkgreen
  :height: 25
.. |ReadKeyStrokeExConformance| image:: https://img.shields.io/badge/ReadKeyStrokeExConformance-darkgreen
  :height: 25
.. |ReadKeyStrokeExFunctionAuto| image:: https://img.shields.io/badge/ReadKeyStrokeExFunctionAuto-darkgreen
  :height: 25
.. |RegisterKeyNotifyConformance| image:: https://img.shields.io/badge/RegisterKeyNotifyConformance-darkgreen
  :height: 25
.. |ResetFunctionAuto| image:: https://img.shields.io/badge/ResetFunctionAuto-darkgreen
  :height: 25
.. |SetStateConformance| image:: https://img.shields.io/badge/SetStateConformance-darkgreen
  :height: 25
.. |UnregisterKeyNotifyConformance| image:: https://img.shields.io/badge/UnregisterKeyNotifyConformance-darkgreen
  :height: 25
.. |Reset_Func| image:: https://img.shields.io/badge/Reset_Func-darkgreen
  :height: 25
.. |ClearScreen_Func| image:: https://img.shields.io/badge/ClearScreen_Func-darkgreen
  :height: 25
.. |EnableCursor_Func| image:: https://img.shields.io/badge/EnableCursor_Func-darkgreen
  :height: 25
.. |OutputString_Func| image:: https://img.shields.io/badge/OutputString_Func-darkgreen
  :height: 25
.. |QueryMode_Conf| image:: https://img.shields.io/badge/QueryMode_Conf-darkgreen
  :height: 25
.. |QueryMode_Func| image:: https://img.shields.io/badge/QueryMode_Func-darkgreen
  :height: 25
.. |Reset_Func| image:: https://img.shields.io/badge/Reset_Func-darkgreen
  :height: 25
.. |SetAttribute_Func| image:: https://img.shields.io/badge/SetAttribute_Func-darkgreen
  :height: 25
.. |SetCursorPosition_Conf| image:: https://img.shields.io/badge/SetCursorPosition_Conf-darkgreen
  :height: 25
.. |SetCursorPosition_Func| image:: https://img.shields.io/badge/SetCursorPosition_Func-darkgreen
  :height: 25
.. |SetMode_Conf| image:: https://img.shields.io/badge/SetMode_Conf-darkgreen
  :height: 25
.. |SetMode_Func| image:: https://img.shields.io/badge/SetMode_Func-darkgreen
  :height: 25
.. |TestString_Func| image:: https://img.shields.io/badge/TestString_Func-darkgreen
  :height: 25
.. |BltVideoBltBuffer_Func| image:: https://img.shields.io/badge/BltVideoBltBuffer_Func-darkgreen
  :height: 25
.. |BltVideoFill_Func| image:: https://img.shields.io/badge/BltVideoFill_Func-darkgreen
  :height: 25
.. |BltVideoToVideo_Func| image:: https://img.shields.io/badge/BltVideoToVideo_Func-darkgreen
  :height: 25
.. |Blt_Conf| image:: https://img.shields.io/badge/Blt_Conf-darkgreen
  :height: 25
.. |QueryMode_Conf| image:: https://img.shields.io/badge/QueryMode_Conf-darkgreen
  :height: 25
.. |QueryMode_Func| image:: https://img.shields.io/badge/QueryMode_Func-darkgreen
  :height: 25
.. |SetMode_Conf| image:: https://img.shields.io/badge/SetMode_Conf-darkgreen
  :height: 25
.. |SetMode_Func| image:: https://img.shields.io/badge/SetMode_Func-darkgreen
  :height: 25

.. |MediaAccessTest| image:: https://img.shields.io/badge/MediaAccessTest-gray
  :height: 25
.. |SCSIBusSupportTest| image:: https://img.shields.io/badge/SCSIBusSupportTest-gray
  :height: 25
.. |ISCSIBootTest| image:: https://img.shields.io/badge/ISCSIBootTest-gray
  :height: 25
.. |USBSupportTest| image:: https://img.shields.io/badge/USBSupportTest-gray
  :height: 25
.. |DebuggerSupportTest| image:: https://img.shields.io/badge/DebuggerSupportTest-gray
  :height: 25
.. |CompressionTest| image:: https://img.shields.io/badge/CompressionTest-gray
  :height: 25
.. |EFIByteCodeTest| image:: https://img.shields.io/badge/EFIByteCodeTest-gray
  :height: 25
.. |TimeStampProtocolTest| image:: https://img.shields.io/badge/TimeStampProtocolTest-gray
  :height: 25
.. |ResetNotificationProtocolTest| image:: https://img.shields.io/badge/ResetNotificationProtocolTest-gray
  :height: 25
.. |TCG2ProtocolTest| image:: https://img.shields.io/badge/TCG2ProtocolTest-gray
  :height: 25
.. |SecureBootTest| image:: https://img.shields.io/badge/SecureBootTest-gray
  :height: 25
.. |BBSRVariableSizeTest| image:: https://img.shields.io/badge/BBSRVariableSizeTest-gray
  :height: 25
.. |ImageLoading| image:: https://img.shields.io/badge/ImageLoading-gray
  :height: 25
.. |VariableAttributes| image:: https://img.shields.io/badge/VariableAttributes-gray
  :height: 25
.. |VariableUpdates| image:: https://img.shields.io/badge/VariableUpdates-gray
  :height: 25
.. |AuthVar_Conf| image:: https://img.shields.io/badge/AuthVar_Conf-gray
  :height: 25
.. |AuthVar_Func| image:: https://img.shields.io/badge/AuthVar_Func-gray
  :height: 25
.. |BBSRVariableSizeTest_func| image:: https://img.shields.io/badge/BBSRVariableSizeTest_func-gray
  :height: 25
.. |ResetSystem_Func| image:: https://img.shields.io/badge/ResetSystem_Func-gray
  :height: 25
.. |ResetSystem| image:: https://img.shields.io/badge/ResetSystem-gray
  :height: 25
.. |PlatformDriverOverrideProtocolTest| image:: https://img.shields.io/badge/PlatformDriverOverrideProtocolTest-gray
  :height: 25
.. |BusSpecificDriverOverrideProtocolTest| image:: https://img.shields.io/badge/BusSpecificDriverOverrideProtocolTest-gray
  :height: 25
.. |DriverDiagnostics2ProtocolTest| image:: https://img.shields.io/badge/DriverDiagnostics2ProtocolTest-gray
  :height: 25
.. |PlatformToDriverConfigurationProtocolT| image:: https://img.shields.io/badge/PlatformToDriverConfigurationProtocolT-gray
  :height: 25
.. |DriverLoaded_Conf| image:: https://img.shields.io/badge/DriverLoaded_Conf-gray
  :height: 25
.. |DriverLoaded_Func| image:: https://img.shields.io/badge/DriverLoaded_Func-gray
  :height: 25
.. |GetDriverPath_Conf| image:: https://img.shields.io/badge/GetDriverPath_Conf-gray
  :height: 25
.. |GetDriverPath_Func| image:: https://img.shields.io/badge/GetDriverPath_Func-gray
  :height: 25
.. |GetDriver_Conf| image:: https://img.shields.io/badge/GetDriver_Conf-gray
  :height: 25
.. |GetDriver_Func| image:: https://img.shields.io/badge/GetDriver_Func-gray
  :height: 25
.. |GetDriver_Conf| image:: https://img.shields.io/badge/GetDriver_Conf-gray
  :height: 25
.. |RunDiagnostics_Conf| image:: https://img.shields.io/badge/RunDiagnostics_Conf-gray
  :height: 25
.. |RunDiagnostics_Func| image:: https://img.shields.io/badge/RunDiagnostics_Func-gray
  :height: 25
.. |CLPCommand| image:: https://img.shields.io/badge/CLPCommand-gray
  :height: 25
.. |CLPErrorValue| image:: https://img.shields.io/badge/CLPErrorValue-gray
  :height: 25
.. |CLPMessageCode| image:: https://img.shields.io/badge/CLPMessageCode-gray
  :height: 25
.. |CLPRetuenString| image:: https://img.shields.io/badge/CLPRetuenString-gray
  :height: 25
.. |CLPReturnStatus| image:: https://img.shields.io/badge/CLPReturnStatus-gray
  :height: 25
.. |Query_Conf| image:: https://img.shields.io/badge/Query_Conf-gray
  :height: 25
.. |Query_Func| image:: https://img.shields.io/badge/Query_Func-gray
  :height: 25
.. |Response_Conf| image:: https://img.shields.io/badge/Response_Conf-gray
  :height: 25
.. |Response_Func| image:: https://img.shields.io/badge/Response_Func-gray
  :height: 25
.. |SimplePointerProtocolTest| image:: https://img.shields.io/badge/SimplePointerProtocolTest-gray
  :height: 25
.. |SerialIOProtocolTest| image:: https://img.shields.io/badge/SerialIOProtocolTest-gray
  :height: 25
.. |AbsolutePointerProtocolTest| image:: https://img.shields.io/badge/AbsolutePointerProtocolTest-gray
  :height: 25
.. |GetState_Func| image:: https://img.shields.io/badge/GetState_Func-gray
  :height: 25
.. |Reset_Func| image:: https://img.shields.io/badge/Reset_Func-gray
  :height: 25
.. |GetControl_Func| image:: https://img.shields.io/badge/GetControl_Func-gray
  :height: 25
.. |Read_Conf| image:: https://img.shields.io/badge/Read_Conf-gray
  :height: 25
.. |Read_Func| image:: https://img.shields.io/badge/Read_Func-gray
  :height: 25
.. |Reset_Func| image:: https://img.shields.io/badge/Reset_Func-gray
  :height: 25
.. |SetAttributes_Conf| image:: https://img.shields.io/badge/SetAttributes_Conf-gray
  :height: 25
.. |SetAttributes_Func| image:: https://img.shields.io/badge/SetAttributes_Func-gray
  :height: 25
.. |SetControl_Conf| image:: https://img.shields.io/badge/SetControl_Conf-gray
  :height: 25
.. |SetControl_Func| image:: https://img.shields.io/badge/SetControl_Func-gray
  :height: 25
.. |Write_Func| image:: https://img.shields.io/badge/Write_Func-gray
  :height: 25
.. |GetState_Conf| image:: https://img.shields.io/badge/GetState_Conf-gray
  :height: 25
.. |GetState_Func| image:: https://img.shields.io/badge/GetState_Func-gray
  :height: 25
.. |Reset_Func| image:: https://img.shields.io/badge/Reset_Func-gray
  :height: 25
.. |UninstallProtocolInterface_Func| image:: https://img.shields.io/badge/UninstallProtocolInterface_Func-darkgreen
  :height: 25

