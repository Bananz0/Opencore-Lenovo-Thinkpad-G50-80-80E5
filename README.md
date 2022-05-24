# Opencore-Lenovo-Thinkpad-G50-80-80E5

<B>OpenCore Hackintosh Monterey 12.3.1 - Lenovo Thinkpad G50-80 80E5</B>

## Quick Installation
- Follow [OpenCore guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) and create a bootable macOS recovery USB
- Download the EFI and place it onto your USB drive
- Boot to OpenCore and setup your disk in Disk Utility

## Specifications

| Specifications      | Detail                                      |
| ------------------- | ------------------------------------------- |
| Computer model      | Lenovo Thinkpad G50-80 80E5                 |
| Processor           | Intel Core i5-5200U Processor               |
| Memory              | 4GB/2GB OEM  / SK Hynix                     |
| HDD		          | Seagate ST1000LM035-1RK172  1TB			 	|
| Integrated Graphics | Intel® HD Graphics 5500                     |
| Monitor             | FHD 1920x1080 (15.6 inch)                   |
| Sound Card          | Conexant CX20751				            |
| Wireless Card       | Intel® Wireless-AC 3160 802.11b/g/n/ac      |
| Ethernet/LAN        | Realtek RTL8168/8111 PCI-E Gigabit Ethernet |
| Card Reader         | Realtek Semiconductor RTS5129 Card Reader   |

## Working
- Intel HD 5500 Acceleration
- CPU Power Management
- Battery Status / Time
- Intel Wireless & Bluetooth 
- Ethernet LAN
- Audio Combo Jack
- Keyboard & Media/Function Keys
- Trackpad & Gestures support
- USB 3.0 and USB 2.0
- Lenovo Easy Camera Webcam
- Sleep/Wakeup & Instant Wake
- Screen LID sleep
- Screen Brightness & F11/F12 Keys


## Not Working
- DRM (No HD playback on Netflix etc)
- WiFi when booting in BootCamp

## Kexts
| Kext                                                                                  
| ------------------------------------------------------------------------------------- | 
| [AirportItlwm](https://github.com/OpenIntelWireless/itlwm)                            |
| [AppleALC](https://github.com/acidanthera/AppleALC)                                   | 
| [BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM)                          | 
| [BrightnessKeys](https://github.com/acidanthera/BrightnessKeys)                       | 
| [ECEnabler](https://github.com/1Revenger1/ECEnabler)                                  | 
| [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | 
| [Lilu](https://github.com/acidanthera/Lilu)                                           | 
| [RTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)                           | 
| [SMCBatteryManager](https://github.com/acidanthera/VirtualSMC)                        | 
| [RealtekCardReader](https://github.com/0xFireWolf/RealtekCardReader)                  | 
| [RealtekCardReaderFriend](https://github.com/0xFireWolf/RealtekCardReaderFriend)      | 
| [SMCProcessor](https://github.com/acidanthera/VirtualSMC)                             | 
| [USBToolBox](https://github.com/USBToolBox/kext)                                      | 
| [UTBMap](https://github.com/USBToolBox/kext)                                          | 
| [VirtualSMC](https://github.com/acidanthera/VirtualSMC)                               | 
| [VoodooPS2](https://github.com/acidanthera/VoodooPS2)                                 | 
| [VoodooSMBUS](https://github.com/VoodooSMBus/VoodooRMI)                               | 
| [WhateverGreen](https://github.com/acidanthera/WhateverGreen)                         | 


## OpenCore
- OpenCore v0.8.0 

## ACPI Patch list
- SSDT-HPET : System Clock fix
- SSDT-EC: Embedded Controller fix
- SSDT-Sleep : Instant wake fix
- SSDT-PNLF : Brightness Fix
- SSDT-SBUS-MCHC : 
- SSDT-PLUG : Allows for native CPU power management



## Credits
- @acidanthera For kexts
- @dortania For guides
- @OpenIntelWireless For AC WiFi & Bluetooth
- @USBToolBox Team for Mapping
- @1Revenger1 for ECEnabler
- @Apple For MacOS
