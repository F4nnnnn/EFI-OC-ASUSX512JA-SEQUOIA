# ASUS Vivobook X512JA Sequoia
This repo contains the efi folders and files needed to run macOS Sequoia on ASUS Vivobook X512J with Open Core. 
This repo includes an OpenCore EFI for the ASUS Vivobook X512JA, and fully working. 

TESTED ON:

MODEL | ASUS VIVOBOOK X512JA
------------- | ---------------
CPU | Intel Core i3-1005G1
iGPU | Intel UHD Graphics G1
RAM | 8 GB DDR4
WiFi | Intel Wireless-AC 9260
macOS | Sequoia 15.7.1

<img src="https://github.com/F4nnnnn/EFI-OC-ASUSX512JA-SEQUOIA/blob/main/About%20This%20Mac.png">

#### I spoofed a quad core i5 for my dual core i3, this is just cosmetics.

### WORK
- [x] Intel integrated graphics
- [x] USB
- [x] Webcam
- [x] Brightness control
- [x] Battery percentage (Charging stops at 61)
- [x] TouchPad w/ Advanced Gestures
- [x] Intel WiFi/ Bluetooth
- [x] SD Card
- [x] Speakers
- [x] Headset Combo Jack
- [x] Apple Services (iCloud, Apple Music, Apple TV, others..)
- [x] Sleep
- [x] DRM also works (Sort of)

### What doesn't work?
- [ ] HDMI
    - Deleted apple driver for Icelake (never fix)
- [ ] Webcam USB2.0 UVC WebCam
    - Some vivobook series Firmware Webcam not supported

## BIOS settings
- Secure Boot: Disabled
- TBD
- AHCI SATA Mode

## Credits

* [acidanthera](https://github.com/acidanthera) (for OpenCore and the kexts)
* [dortania](https://dortania.github.io/OpenCore-Install-Guide/) (for their awesome guide)
* [VoodooI2C](https://github.com/VoodooI2C) (for VoodooI2C)
* [OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm) (for Intel WiFi)
* our tester
