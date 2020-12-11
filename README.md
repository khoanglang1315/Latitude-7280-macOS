# macOS on Dell Latitude 7280
This repository contains a sample configuration to run macOS (Currently Catalina 10.15.3 build 19D76) on a Dell Latitude 7280

# Hardware Configuration
* intel i5-7300u
* Micron DDR4 2400MHz 8GB
* NVME SM961 256GB
* 1366 * 768 resolution display 
* DW1560/BCM94352Z (replace intel wireless card)
* To be supplemented

# Current working
* display
* sound/mic (earphone supported)
* network (wired and wireless)
* bluetooth
* keyboard (include shortcuts for volume control(Fn + F1/F2/F3)
* touchpad (one finger and two finger gestures)
* usb
* hdmi/type-c(only dp tested)
* battery
* better CPU frequency conversion (rely on CPUFriend)
* webcam

# Untested or not working
* sd card

# Kexts
* ACPIBatteryManager.kext
* AirportBrcmFixup.kext
* AppleALC.kext
* AppleBacklightFixup.kext
* CPUFriend.kext & CPUFriendDataProvider.kext
* FakeSMC.kext
* IntelMausiEthernet.kext
* Lilu.kext
* USBInjectAll.kext
* UVC2FaceTimeHD.kext
* VoodooI2C.kext
* VoodooI2CHID.kext
* VoodooPS2Controller.kext
* WhateverGreen.kext
