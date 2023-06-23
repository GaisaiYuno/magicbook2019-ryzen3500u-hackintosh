# magicbook2019-ryzen3500u-hackintosh

An OpenCore config for Magicbook 2019 (Ryzen Edition)

OpenCore version: 0.7.8

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


### What is not working

* Hibernation

* Touchpad (Please share the files with me or pull request if fixed)

* Front Camera

### Credits

* Apple for macOS

* https://github.com/pondsmile/EFI-Lenovo-Ideapad-C340-Hackintosh

* https://github.com/NootInc/NootedRed
