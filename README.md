# magicbook2019-ryzen-hackintosh

An OpenCore config for Magicbook 2019 (Ryzen Edition)

OpenCore version: 0.7.8

macOS: 10.15.6 (19G73)

- CPU: AMD Ryzen 5 3500U
- Display: AMD Radeon Vega 8
- Network: Intel wireless 8265 / 8275
- Hard-disk: Samsung MZVLB256HAHQ (pm981)

Use paragon hard disk manager 16.5 to recover. Check [wendao2008/Matebook-D14-2020-hackintosh-Pm981](https://github.com/wendao2008/Matebook-D14-2020-hackintosh-Pm981)

Please change MLB/ROM/Serial Number/UUID.

### What is working

* CPU monitoring (using amd power gadget app)

* Network (using Heilport app)

* Bluetooth

* Touchpad

### What is not working

* Graphics

* Hibernation and random startup problems (probably caused by pm981)

* Audio (broken sound)

* Camera

### Credits

* Apple for macOS

* https://github.com/iamthaoly/amd-laptop-hackintosh for CPU support

* [wendao2008/Matebook-D14-2020-hackintosh-Pm981](https://github.com/wendao2008/Matebook-D14-2020-hackintosh-Pm981) for pm981 support
