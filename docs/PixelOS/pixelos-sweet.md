![](pixelos.png)
# PixelOS
[**PixelOS**](https://pixelos.net/download/sweet) is an AOSP based ROM, with Google apps
included and all Pixel goodies. We aim to provide
an experience similar to Google Pixel phones with
numerous performance enhancements and a small
amount of useful additional features.


- Device: Redmi Note 10 Pro
- Codename: ``sweet / sweetin``
- Maintainers: [Aryan](https://github.com/basamaryan)
- Group Support: [Telegram](https://t.me/Aryannn999)
- Support PixelOS: [Paypal](https://paypal.me/whyredfire)

---

### Custom Recovery
- **OrangeFox Recovery** ``R11.1_7`` **EROFSCompression** - [Download](https://github.com/basamaryan/android_device_xiaomi_sweet-TWRP/releases/download/R11.1_7/OrangeFox-R11.1_7-Unofficial-sweet-EROFSCompression.zip)

### Firmware Only

**Redmi Note 10 Pro**
| Region | Version | Link |
| :-: | :-: | :-: |
| Global | ``V14.0.8.0.TKFMIXM`` | [**Download**](https://cloud03.faultx.workers.dev/0:/Firmware/Firmware%20Only%20(FW)/Global%20(MI)/14.0.8/fw_sweet_miui_SWEETGlobal_V14.0.8.0.TKFMIXM_3e19ed98ed_13.0.zip?a=view)
| EEA | ``V14.0.9.0.TKFEUXM`` | [**Download**](https://cloud03.faultx.workers.dev/0:/Firmware/Firmware%20Only%20(FW)/Europe%20(EU)/14.0.9/fw_sweet_miui_SWEETEEAGlobal_V14.0.9.0.TKFEUXM_79417d5d99_13.0.zip?a=view)
| Indonesia | ``V14.0.2.0.TKFIDXM`` | [**Download**](https://cloud03.faultx.workers.dev/0:/Firmware/Firmware%20Only%20(FW)/Indonesia%20(ID)/14.0.2/fw_sweet_miui_SWEETIDGlobal_V14.0.2.0.TKFIDXM_df828d33c5_13.0.zip?a=view)

**Redmi Note 10 Pro / Pro Max (India)**
| Region | Version | Link |
| :-: | :-: | :-: |
|India|``V14.0.1.0.TKFINXM``|[**Download**](https://xmfirmwareupdater.com/firmware/sweetin/stable/V14.0.1.0.TKFINXM/)

---

### Android 16
| File Name | Release | Build | MD5 | Link |
| :-: | :-: | :-: | :-: | :-: |
| - | - | - | - | - |


### Android 15
| File Name | Build | MD5 | Link |
| :-: | :-: | :-: |:-: |
| PixelOS_sweet-15.0-20250517-1357.zip | 2025-05-17 | ``9d9fdde18e524b033c027a14e2ac7e94`` | [Download](https://sourceforge.net/projects/pixelos-releases/files/fifteen/sweet/PixelOS_sweet-15.0-20250517-1357.zip/download) |
| PixelOS_sweet-15.0-20250505-1620.zip | 2025-05-05 | ``540d6fddcac5f301eda807df8f913b99`` | [Download](https://sourceforge.net/projects/pixelos-releases/files/fifteen/sweet/PixelOS_sweet-15.0-20250505-1620.zip/download) |
| PixelOS_sweet-15.0-20250117-2309.zip | 2025-01-17 | ``65af2151fa2b0b5b38d3c8c6e0a7e2da`` | [Download](https://sourceforge.net/projects/pixelos-releases/files/fifteen/sweet/PixelOS_sweet-15.0-20250117-2309.zip/download) |

---

### Android 14
| File Name | Build | MD5 | Link |
| :-: | :-: | :-: | :-: |
| PixelOS_sweet-14.0-20241026-0519.zip | 2024-10-26| ``e0c6e5913373c4bd4f403a99d6bf539a`` | [Download](https://sourceforge.net/projects/pixelos-releases/files/fourteen/sweet/PixelOS_sweet-14.0-20241026-0519.zip/download) |

[Old version - Download ➜](https://sourceforge.net/projects/pixelos-releases/files/fourteen/sweet/)


### Android 13
| File Name | Build | MD5 | Link |
| :-: | :-: | :-: | :-: |
| PixelOS_sweet-13.0-20230831-0536.zip| 2023-08-31 | ``d4211e74fd672c5a4c751bda67ea1ec6`` | [Download](https://sourceforge.net/projects/pixelos-releases/files/thirteen/sweet/PixelOS_sweet-13.0-20230831-0536.zip/download) |

[Old version - Download ➜](https://sourceforge.net/projects/pixelos-releases/files/thirteen/sweet/)


### Android 12
| File Name | Release | MD5 | Link |
| :-: | :-: | :-: | :-: |
| PixelOS_sweet-12.1-20220812-0031.zip | 2022-08-12 | ``ce4895f8a3cf2af7fd5b659986fea5ce`` | [Download](https://sourceforge.net/projects/pixelos-releases/files/twelve/sweet/PixelOS_sweet-12.1-20220812-0031.zip/download) |


[Old version - Download ➜](https://sourceforge.net/projects/pixelos-releases/files/twelve/sweet/)

---

## Installation Guide

### Flash with Orangefox (Clean flash)
- Download **OrangeFox Recovery R11.1_7** ``EROFSCompression`` - [Download](https://github.com/basamaryan/android_device_xiaomi_sweet-TWRP/releases/download/R11.1_7/OrangeFox-R11.1_7-Unofficial-sweet-EROFSCompression.zip)
- Reboot the device to **recovery**
- Flash **OrangeFox Recovery R11.1_7**
- Reboot to Recovery
- Flash Firmware Only (Optional)
- Flash PixelOS ROM ``.zip``
- Format Data **"Yes"**
- Reboot and voila!

### Flash with Orangefox (Dirty flash / Update)
- Reboot the device to **recovery**
- Flash PixelOS ROM ``.zip``
- Reboot and voila!

### Clean flash (coming from a different ROM)
Clean flash involves formatting data which means you will be loosing data stored in the internal storage of your device, data in SD Card should not be affected. I will not be responsible for any loss of data.

- Download ROM and recovery files to your computer
- Reboot the device to bootloader **(Fastboot Mode)**
- Flash the recovery by running ``fastboot flash recovery <path/to/recovery.img>`` in terminal/CMD
- Reboot to recovery by holding **volume up + power button**
- Go to **Advanced > Enable ADB Sideload**
- Flash the latest MIUI 14 firmware for your region through ADB sideload by running ``adb sideload <path/to/firmware.zip>``
- Flash the ROM through ADB sideload by running ``adb sideload <path/to/rom.zip>`` in terminal/CMD
- Go to **Main menu > Wipe > Format Data > Type "yes" and confirm**
- Reboot and voila!

### Dirty Flash / Update
There will be no loss of data if everything goes well. Keep backups incase of any mishap. I will not be responsible for any loss of data.

- Download ROM file to your computer
- Reboot the device to **recovery**
- On your phone [which is in recovery mode], go to **Advanced > Enable ADB Sideload**
- Flash the ROM through ADB sideload by running ``adb sideload <path/to/rom.zip>`` in terminal/CMD
- Reboot and voila!

---
[**← Back**](https://github.com/TriHermawan/RedmiNote10Pro?tab=readme-ov-file#table-of-contents)
