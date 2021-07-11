# Asus-Vivobook-X509JB-Hackintosh
EFI for ASUS X509 with OpenCore bootloader

### Specifications:

| Component            | Name                                                     |
| -------------------- | -------------------------------------------------------- |
| CPU                  | Intel i3 1005G1 (2C-4T 4MB ICL)                          |
| iGPU                 | Intel® UHD Graphics for 10th Gen Intel® Processors       |
| dGPU (disabled)      | Nvidia MX110                                             |
| Audio                | Realtek ALC256 [(layout-id:66)](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs) |
| Ram                  | 8 GB DDR4 2667 Mhz                                       |
| Display (unrelated?) | Monitor: N156HGA-EA3 15.6 FHD (replaced with N156HCE-EN1)|
| Wifi + Bluetooth     | Intel 9461                                               |
| NVMe                 | SK Hynix BC501 256 GB (Windows+macOS)                    |
| SmBios               | MacBookAir 9,1                                           |
| BootLoader           | OpenCore 0.7.1                                           |
| macOS                | Big Sur 11.4                                             |
| macOS                | Catalina 10.15.7                                         |

### What works and What doesn't or WIP:

- [x] Intel Iris Plus iGPU eDP with Backlight Output
- [ ] Intel Iris Plus iGPU HDMI Output (Not supported at the moment)
- [ ] Intel Iris Plus iGPU Type-C to HDMI Output (Not supported at the moment?)
- [x] Intel Iris Plus iGPU - H264 & HEVC (todo: test)
- [x] ALC256 Internal Speakers
- [x] ALC256 Internal microphone
- [x] ALC256 Combojack headphones
- [ ] ALC256 Combojack microphone
- [ ] ALC256 HDMI Audio Output (Not supported at the moment)
- [ ] ALC256 TYPE-C to HDMI Audio Output (Not supported at the moment?)
- [x] All USB-A 3.1 Ports (TYPE-C 3.2 Included)
- [x] SpeedStep / Sleep / Wake
- [x] HID Key PWRB & SLPB (todo: test)
- [x] I2C Touchpad with gesture
- [x] Keyboard (PS2-Internal) no backlight
- [x] F5 & F6 Brightness Key
- [ ] F10 Print Screen Key
- [x] F1 & F2 & F3 Sound Key
- [x] Wi-Fi and Bluetooth (todo: test bluetooth) Intel 9461 (DW1830) Module
- [x] SSD NVME Slot-1 PciE Gen3x4
- [ ] SSD NVME Slot-2 PciE Gen3x4 (is this the one replacing wwan? not tested.)
- [ ] Micro SD Cardreader (USB-Internal) (todo: teste)
- [x] WebCam (USB-Internal)
- [ ] All Sensors CPU, IGPU, BATTERY, NVME, FAN (todo: test)
- [x] ACPI Battery
- [x] NVRAM (Native) (todo: native?)
- [x] Recovery (macOS) boot from OpenCore (todo: test)
- [x] Windows 10 boot from OpenCore

### Special Config:
- Usb port mapping performed

### MacOS bootable USB creation:

Read the Dortania guide for creating your USB from Windows or macOS
Guide Dortania - USB creation

### Credits
- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.
- [Hackintoshlifeit](https://github.com/Hackintoshlifeit) Support group for installation and post installation.
- [Lorys89](https://github.com/Lorys89/DELL_VOSTRO_5401-ICE-LAKE) for his README used here as a reference.
