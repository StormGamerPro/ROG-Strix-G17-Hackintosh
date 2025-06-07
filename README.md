## ROG Strix G17 Hackintosh
Asus ROG Strix G17 G713QM Hackintosh Opencore

<div align="center">
  <img src="https://github.com/StormGamerPro/ROG-Strix-G17-Hackintosh/blob/main/screenshot.jpeg">
</div>

# Specs

| Type | Hardware | 
| ------------- | ------------- | 
|  GPU | Nvidia RTX 3060  | 
|  IGPU | AMD RX Vega 8  |
|  CPU | AMD Ryzen 9 5900HX  |
|  RAM | 16 GB 3200MHz DDR4 |
|  WIFI | Intel Wi-Fi 6 AX200 |
|  Ethernet | Realtek RTL8111 |

# Whats working

- **AMD RX Vega 8**  
- **Intel Wi-Fi 6 AX200**   
- **Realtek RTL8111**  
- **Touchpad**  
- **Audio/Mic**  
- **Boot-Up Sound**  
- **USB/USB-C Ports**  
- **HDMI**  
- **WIFI**  
- **Battery Status**   
- **Volume Keys**  
- **Brightness**  
- **Handoff partially working**  
- **Booting Linux/Windows through Opencore**  
- **144Hz on Laptop Screen and over HDMI**  
- **Every macOS version from Catalina to Sequoia 15.5**

# Whats not working/issues

- **Nvidia RTX 3060:** Not supported  
- **Audio over HDMI:** known issue of NootedRed  
- **Proper Sleep:** RGB just turns off  
- **Brightness keys:** Use keyboard shortcuts  
- **Airdrop:** cant receive and send  
- **No native WIFI on Sequoia and Catalina:** Use Heliport  
- **Bluetooth sometimes breaks on Sequoia:** Boot into Sonoma/Ventura to fix  
- **OOBE from Sequoia with NootedRed:** Use the EFI located in the Sequoia folder   
- **Bluetooth showing device but not connecting on Monterey and Higher**  
- **Freezes on Catalina, Sonoma and Sequoia** 


# Notes

The EFI in the Sequoia folder is just for the installation of macOS Sequoia.  
Please revert back to the EFI in the Standart folder after installation.  
For normal usage you should use the EFI in the Standart folder.  
