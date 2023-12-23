# Lenovo ThinkPad T14s Gen 1 - macOS Sonoma - OpenCore 9.5

<img src="/img/Screenshot.png" alt="macOS Sonoma - T14s Gen 1" width="425">


**DISCLAIMER:**  
I am not responsible for any damages you may cause.  
Should you find an error or improve anything — whether in the config or in the documentation — please consider opening an issue or pull request.

&nbsp;

## 💻 My Hardware

| Category  | Component                                  |
| --------- | ------------------------------------------ |
| CPU       | Intel(R) Core(TM) i5-10310U CPU @ 1.70GHz  |
| GPU       | Intel UHD Graphics 620                     |
| SSD       | Crucial P3 1TB PCIe M.2 2280 SSD           |
| SD        | MicroSD card slot                          |
| Memory    | 8 GB DDR4 @ 2666MHz                        |
| Camera    | 720p Camera + IR Camera                    |
| Audio     | Realtek HDA ALC257 (aka ALC3287)           |
| WiFi & BT | Intel Wi-Fi 6 AX201 802.11ax 2x2 with BT5.2 (Soldered on)           |
| Display   | 14" Full HD (1920x1080)                     |

&nbsp;

## 🏗️ Preparation

<summary><strong>Download macOS Sonoma</strong></summary>
1. Following [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html) download latest macOS Sonoma version.
  Using the App Store is the easyiest way if you are already running a macOS, even throgh a VM. Command Line Software Update Utility its pretty easy too. Format and setup installer according to the guide.
2. Copy the provided EFI folder to EFI partion in the USB drive.
3. Reboot and install macOS, Wifi should be available during install.
</br>


&nbsp;

## 🧰 Post-Install (Optional)

<summary><strong>YogaSMCPanel</strong></summary>
</br>

1. Install [YogaSMCPanel](https://github.com/zhen-zen/YogaSMC)


&nbsp;


## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.
- [Baio1977](https://github.com/Baio1977/) Ventura EFI for T14 Gen 1.
- [askwakhid](https://github.com/askwakhid/ThinkPad-T14-macOS-OpenCore/tree/main) Ventura EFI for T14 Gen 1.
