![](lineageos.png)
# LineageOS
[**LineageOS**](https://lineageos.org/) A free and open-source operating system for various devices, based on the Android mobile platform.

```
Device   : Redmi Note 10 Pro / Pro Max
Codename : sweet / sweetin
----------------------------------------------------------------------
Maintainers       : Aryan & danielml3
Group Support     : Telegram (https://t.me/lineagesweet)
Support LineageOS : Paypal (https://www.paypal.com/paypalme/LineageOS)
```

---

> [!NOTE]
> Use LineageOS Recovery (**Recommended**)


## Firmware Only

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

## Download 
- [ROM & Recovery](https://download.lineageos.org/devices/sweet/builds)

## GApps (Google Apps)
- Android 16 
  - [MindTheGapps](https://github.com/MindTheGapps/16.0.0-arm64/releases/latest)
- Android 15 
  - [MindTheGapps](https://github.com/MindTheGapps/15.0.0-arm64/releases/latest)
- Android 14
  - [MindTheGapps](https://github.com/MindTheGapps/14.0.0-arm64/releases/latest)



## Installation Guide
1. **Unlock Bootloader**
    - Ensure your device's bootloader is unlocked before proceeding.
2. **Reboot To Fastboot**
    - Reboot to Fastboot by pressing Vol Down + Power Button.
3. **Connection**
    - Open CMD or Terminal on your PC and connect your phone via USB.
4. **Flash Recovery**
    - Flash recovery by typing:
       - ```
         fastboot flash recovery recovery.img
         ```
5. **Reboot To Recovery**
    - Reboot into Recovery typing:
       - ```
         fastboot reboot recovery
         ```
6. **Format Data**
    - Tap Factory Reset, then Format data / factory reset and continue with the formatting process. This will remove encryption and delete all files stored in the internal storage, as well as format your cache partition (if you have one).
7. **Flash Firmware** (_Optional_)
    - (_If you were previously on the latest version of MIUI 14 stock ROM, there is no need to flash the firmware_). 
    - In LineageOS Recovery select “Apply Update”, then “Apply from ADB” to begin sideload.
      - ```
        adb -d sideload firmware.zip
        ```
8. **Install LineageOS ROM**
    - ```
      adb -d sideload lineage-23.0-xxxxxxxx-nightly-sweet-signed.zip
      ```
9. **Install GApps** (_Optional_)
    - Click Apply Update, then Apply from ADB,
      - ```
        adb -d sideload MindTheGapps-16.0.0-arm64-xxxxxxxx_xxxxxx.zip
        ```
      When presented with a screen that says **Signature verification failed**, click **Yes**. It is expected as add-ons aren’t signed with LineageOS’s official key!
10. **Reboot System**
    - Click the back arrow in the top left of the screen, then **“Reboot system now”**.

---
