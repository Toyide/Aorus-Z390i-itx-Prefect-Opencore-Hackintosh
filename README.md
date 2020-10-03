# Aorus-Z390i-itx-Prefect-Opencore-Hackintosh

- On board wifi and bluetooth, no need swap wifi cards
- 无需转接卡 直接驱动自带的AC 9560 完美黑苹果

### Specs:
- i9 9900ks @ 5.0ghz 
- Aorus Z390i pro wifi itx motherboard
- Radeon RX 5700 GPU
- onboard wifi & bluetooth AC 9560 Cnvi
- Dual boot windows and macos catalina

### Credit to:
- Opencore 6.1
- IntelBluetoothFirmware 1.1.2
- AirportItlwm_v1.0_Beta_Catalina
- [smithc42 project](https://github.com/smithc42/hackintosh_gigabyte_z390i)
- UtterDisbelief @tonymacx86
- USB mapping tool: HackinTool

### Steps to get it working:
- 1.Unlock CFG
- 2.enable onboard wifi
- 3.turn off above 4g Decoding (I crashed my bios everytime when enable it)
(or check other guides for bios setting if you can't get to post.)
- 4.modify config to your own serial number, MLB, SystemUUID.
- 5.move files to EFI folder on your usb driver or internal drive

### Note
- I mapped 07 and 08 port as usb 2.0 for my mouse and keyboard, change it by generate another USBports.kext with HackinTool as needed.
- You will have to set usb mapping correct to get Intel onboard wifi bt working.

### To be done
- Wifi speed

### Useful Links
[USB mapping](https://www.tonymacx86.com/threads/the-new-beginners-guide-to-usb-port-configuration.286553/)
[OpenIntelWireless](https://github.com/OpenIntelWireless) (Awesome project!)
