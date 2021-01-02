# HP X360 Pavilion 14-dw0004nl

EFI for HP X360 Pavilion 14-dw0004nl Ice Lake with OpenCore bootloader

![descrizione](./Screenshot/pc.jpg)

### Computer Spec:

| Component        | Brank                              |
| ---------------- | ---------------------------------- |
| CPU              | Intel i5 10635G1 (4C-8T 8MB ICL)   |
| iGPU             | Intel® UHD630          			|
| Lan              | NO-LAN                       		|
| Audio            | Realtek ALC287                     |
| Ram              | 1x8GB DDR4 3200 Mhz SODIMM			|
| Wifi + Bluetooth | RTL8822CE 802.11ac PciE		    |
| NVMe             | HYNIX SK PM401 256GB  	   	 	    |
| SmBios           | MacBookPro 16,2                    |
| BootLoader       | OpenCore  0.6.4                    |

![infobigsur](./Screenshot/infomacbigsur.png)

### What works and What doesn't or WIP:

- [x] Intel UHD630 iGPU eDP with Backlight Output
- [ ] Intel UHD630 iGPU HDMI Output (Not supported at the moment)
- [ ] Intel UHD630 iGPU Type-C to HDMI Output (Not supported at the moment)
- [x] ALC287 Internal Speakers
- [x] ALC287 Internal microphone
- [x] ALC287 Combojack headphones
- [ ] ALC287 Combojack microphone
- [ ] ALC287 HDMI Audio Output (Not supported at the moment)
- [ ] ALC287 TYPE-C to HDMI Audio Output (Not supported at the moment)
- [x] All USB-A 3.1 Ports (TYPE-C 3.2 Included)
- [x] SpeedStep / Sleep / Wake
- [x] HID Key PWRB & SLPB
- [x] I2C Touchscreen
- [x] I2C Touchpad with gesture (Partial work)
- [x] Keyboard with backlight
- [x] Brightness Key
- [ ] Wi-Fi and Bluetooth Native (to change w/ BCM943602BAED DW1830)
- [x] SSD NVME Slot-1 PCIe Gen3x4
- [x] Micro SD Card Reader (PCIe RTS522A)
- [x] WebCam (USB-Internal)
- [x] ACPI Battery
- [x] NVRAM (Native)


## Peripherals

![infohack](./Screenshot/periferiche.png)
![infodp2](./Screenshot/pci-list.png)
![infopci](./Screenshot/pci-dev.png)

### Special Config:

- Usb port mapping performed
- SSDT-Hack Essential patch
- Applied cosmetics PCI Dev

See [ioreg](./ioreg%20MacBook%20Pro%2016%2C2.ioreg) for more clarification

## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.
- [Hackintoshlifeit](https://github.com/Hackintoshlifeit) Support group for installation and post installation.

# If you need help please contact us on [Telegram](https://t.me/HackintoshLife_it) or [Web](https://www.hackintoshlife.it/)
