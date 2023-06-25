# magicbook2019-ryzen3500u-hackintosh

[中文说明](/README-CN.md)

![image](https://github.com/GaisaiYuno/magicbook2019-ryzen3500u-hackintosh/assets/52853137/534da580-53c8-4330-a09f-cb8017922020)


An OpenCore config for Magicbook 2019 (Ryzen Edition)

OpenCore version: 0.9.3

macOS: 11.7.7

- CPU: AMD Ryzen 5 3500U
- Display: AMD Radeon Vega 8 (Working on VRAM 2GB)
- Network: Intel wireless 8265 / 8275
- Hard-disk: Samsung MZVLB256HAHQ (pm981) (It was upgraded to SN570 afterwards)
- RAM: 8GB

Please change MLB/ROM/Serial Number/UUID.

### What is working

- Graphic Acceleration (using NootedRed.kext)

* CPU Monitoring (using AMD Power Gadget app)

* Network

* Bluetooth

* Battery Status

* Audio (AppleALC layout-id=57)

* USB (Follow the instructions)
  * Download [UniversalAMDFormBrowser.zip](https://github.com/DavidS95/Smokeless_UMAF/blob/main/UniversalAMDFormBrowser.zip)
  * Format a pendrive in FAT32 and copy content to root
  * Boot from pendrive
  * Navigate to Device Properties > AMD CBS > FCH Common Options > USB Configuration Options > **XHCI1** Controller Enable: Change to Disabled
  * Esc to back and press Y when prompted to save, Esc to back, then Reset on first menu (not continue)
* Touchpad (working under polling mode, by adding `-vi2c-force-polling` into boot-args)


### What is not working

* Hibernation
* Front Camera (connected to XHC, which is disabled)

### Detailed Information

https://github.com/GaisaiYuno/magicbook2019-ryzen3500u-hackintosh/issues/1

### Credits

* Apple for macOS

* https://github.com/pondsmile/EFI-Lenovo-Ideapad-C340-Hackintosh

* https://github.com/NootInc/NootedRed

