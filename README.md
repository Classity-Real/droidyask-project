<p align="center">
  <img src="assets/homeworkdirartifactsaetherkernel_banner-1.png" alt="AetherKernel" width="100%" />
</p>

# AetherKernel: Based on BakaSU
Custom kernel for Snapdragon 680 Devices.
Built with BakaSU and SUSFS, plus DroidSpace support.

## Devices
- Xiaomi Pad SE: Tested and working successfully
- Other Snapdragon 680: Not Tested yet

## What you need

- A Supported Device
- Unlocked bootloader
- Lineage Recovery, or TWRP
- ADB (if flashing from a PC)

## Install

1. Grab the AnyKernel zip from Releases.
2. Boot into TWRP.
3. Sideload the zip (`adb sideload <zip>`) or install it from the tablet.
4. When prompted, pick CLO or GKI, then KSU Only.
5. Reboot.
6. Install the BakaSU manager.

Make a backup before flashing.

## Credits 1: Regular
- PhamtomK12 - original builder
- ssocozy - idk... ;)
- NVG-064 - idk... ;)
- ShirkNeko - SUSFS
- Classity_Real - DroidSpace integration
### Credits 2: BakaSU 
- [KernelSU](https://github.com/tiann/KernelSU): upstream
- [SukiSU-Ultra/SukiSU-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra): fork source
- [Kernel-Assisted Superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): The KernelSU idea.
- [Magisk](https://github.com/topjohnwu/Magisk): The powerful root tool.
- [genuine](https://github.com/brevent/genuine/): APK v2 signature validation.
- [Diamorphine](https://github.com/m0nad/Diamorphine): Some rootkit skills.
