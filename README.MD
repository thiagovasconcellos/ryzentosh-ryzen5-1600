# AMD Ryzen Hackintosh

[![MacOS version](https://img.shields.io/badge/macOS-11.5%20Beta%2020G5033c-informational.svg)](https://www.apple.com/macos)
[![OpenCore version](https://img.shields.io/badge/OpenCore-0.7.0-informational.svg)](https://github.com/acidanthera/OpenCorePkg)
[![GitHub](https://img.shields.io/github/license/sileshn/Ryzentosh?style=flat-square)](https://github.com/sileshn/Ryzentosh/blob/master/LICENSE)

# Be aware
Use at your own risk. I take no responsiblity if your rig explodes. Create unique SMBios values for your rig. **DO NOT** copy ones shown in the config.plist.

* I removed the BigSur dmg from com.apple.recovery.boot. You should [download the dmg and place it there](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html#downloading-macos)

* If it is your first time, **DO NOT** quick read the manual and then try to follow along! I've tried that and it took me 48 hours to figure out WTH was going on. Read every instruction carefully

[![Os](https://i.ibb.co/pwBb6r1/Screenshot-at-Jun-14-17-11-05.png)](https://ibb.co/XLrjfkW)

## Specification

| Component        | Model                                  |
| ---------------- | -------------------------------------- |
| CPU              | AMD Ryzen 5 1600                       |
| MotherBoard      | Biostar Racing B350GTX                 |
| OS Disk          | Kingston 240gb SSD                     |
| RAM              | 2x 8gb HyperX Fury (16GB Ram)          |
| GPU              | Radeon RX 550 4gb Graffiti Series      |

## Working

* Audio
* Ethernet
* iServices

## Not Working ( only ones I have tried, there may be more )

* Drm related stuff ( Apple TV )
* Bluetooth (I don't need it)

## Patches, Drivers & Kexts

* [Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla)
* [OpenRuntime](https://github.com/acidanthera/OpenCorePkg)
* [OpenCanopy](https://github.com/acidanthera/OpenCorePkg)
* [OpenHfsPlus](https://github.com/acidanthera/OpenCorePkg) 
* [Lilu](https://github.com/acidanthera/Lilu)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
* [AppleALC](https://github.com/acidanthera/AppleALC)
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
* [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
* [RestrictEvents](https://github.com/acidanthera/RestrictEvents)
* [AMDRyzenCPUPowerManagement](https://github.com/trulyspinach/SMCAMDProcessor)
* [SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor)
* [AppleMCEReporterDisabler](https://github.com/AMD-OSX/AMD_Vanilla/blob/opencore/ExtraAppleMCEReporterDisabler.kext.zip)

## Credits and links

* [OpenCore Desktop Guide](https://github.com/dortania/OpenCore-Desktop-Guide)