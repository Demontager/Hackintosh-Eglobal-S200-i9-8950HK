
Hackintosh Monterey/Ventura on NUC-like S200-i9-8950HK

Fully working Opencore config for [Eglobal S200](https://www.aliexpress.com/item/4000465233975.html)  

- Motherboard: Eglobal S200 Bios ver. VM206
- CPU: Intel i9-8950HK Coffee Lake
- RAM: 32GB Corsair 2xCMSO32GX4M2A2133C15 DDR4
- Storage: Samsung 970 EVO M.2 512GB
- iGPU: Intel UHD 630
- WIFI/BT: Intel 3165ngw (Internal M.2 E Key 2230)
- SMIBIOS: macmini8,1
- OpenCore 0.8.4 RELEASE

![Screen Shot 2022-10-02 at 11 57 36 AM](https://user-images.githubusercontent.com/7040503/193446479-283ad0fc-ba25-4f5d-b9a0-796ab700c5b8.png)
![Scr48 50 PM](https://user-images.githubusercontent.com/7040503/226114861-c9c86d51-2113-462c-bcdd-a7d10939f64d.png)


## BIOS SETTINGS
- Default settings
- Note: Enable CSM support if keyboard unresponsible in OCR menu


## Tested and found working:
- Boot into MacOS 12.6
- Display Port / HDMI output
- Internal Audio Realtek ALC269
- Sleep Wake up from bluetooth mouse or keyboard
- iGPU hardware acceleration
- WIFI and Bluetooth 
- Internal Gigabit Network Card RTL8111/8168/8411

## Tools used:
- [Opencore](https://dortania.github.io/OpenCore-Install-Guide/) 
- [ProperTree](https://github.com/corpnewt/ProperTree)
- [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/)
- [Hackintool](https://github.com/headkaze/Hackintool)
- [SSDTTime](https://github.com/corpnewt/SSDTTime)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- [IORegistryExplorer](https://github.com/vulgo/IORegistryExplorer)

## Guides:
- [Custom SSDT's with SSDTTime](https://www.tonymacx86.com/threads/custom-ssdts-using-corpnewts-ssdttime.318976/)
- [Making own USB port map](https://www.tonymacx86.com/threads/the-new-beginners-guide-to-usb-port-configuration.286553/#post-2029768)
- [How to map your USB Ports on macOS](https://elitemacx86.com/threads/how-to-map-your-usb-ports-on-macos.581/)
- [Intel UHD 630 iGPU configuration](https://www.tonymacx86.com/threads/guide-intel-uhd-graphics-630-coffee-lake-headless-mode-main-card.304000/)
- [Eglobal S200 forum thread](https://www.tonymacx86.com/threads/eglobal-s200-nuc-intel-i7-8750h-mini-pc-compatible.276741/) 


## Geekbench Tests
![Screen Shot 2022-10-02 at 12 34 27 PM](https://user-images.githubusercontent.com/7040503/193447680-8ca444b9-2fb2-4fca-ac2e-709294edb10a.png)
![Screen Shot 2022-10-02 at 12 03 53 PM](https://user-images.githubusercontent.com/7040503/193446592-f12e6261-ca0a-497e-8122-1927870871d9.png)
![Screen Shot 2022-10-02 at 12 05 13 PM](https://user-images.githubusercontent.com/7040503/193446639-a4f40def-9ecb-4bfc-a287-1e4d61b07222.png)

