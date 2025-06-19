<!-- <img src="https://lh3.googleusercontent.com/pw/AP1GczPLAEv6uUnzAHhMsTsrVDfBvyOfTeNwL56cy_6scp6g_glrnzhjKOyNSQaf2pbI_4_GkJlDBwI_jWj1l9QewYb5P4Wwz0lKV1JuZ881kPNC7B-kbwc3qvVdEkUpJNqjkzPojcz8wKo8TGOCMuHjXaQbTA=w2880-h696-s-no" alt="" width="" height=""> -->


<p align="center">
  <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/install-los-pict/los-logo.png" alt="Picture" width="350" height="auto">
</p>


# Install LineageOS

```
Device   : Redmi Note 10 Pro
codename : sweet
```
➜ [Official guide](https://wiki.lineageos.org/devices/sweet/install/variant1/#)

> [!Caution]
> Saya tidak bertanggung jawab atas apa pun yang terjadi pada perangkat kamu. Lakukan dengan risiko kamu sendiri!
>
> [`FaultX`](https://t.me/faultx003)

---

## Download
- [LineageOS ROM & Recovery](https://download.lineageos.org/devices/sweet/builds)
  
  <details>
       <summary>Picture</summary>
        <p align="center">
          <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/install-los-pict/los-download.png" alt="Picture" width="" height="">
        </p>
    </details>
    
   Rename:
  - `lineage-xx.x-xxxx-nightly-sweet-signed.zip` ➜ `rom.zip`
    
- [Latest Firmware Only](./README_ID.md#firmware)

  Rename: `fw_sweet_miui_xxxxx_13.0.zip` ➜ `fw.zip`
- Optional:
  - [MindTheGApps](./README_ID.md#gapps-google-apps)

    Rename: `MindTheGapps-15.0.0-arm64-xxxxx.zip` ➜ `gapps.zip`
  - [Magisk](https://github.com/topjohnwu/Magisk/releases/tag/v28.1)

    Rename: `Magisk-xxxx.apk` ➜ `magisk.zip`

### Syarat
- Pastikan [ADB & Fastboot Driver](./install-adb-fastboot.md) sudah terinstall dengan benar di mesin komputer anda.
- Backup semua data penting, karena data akan terformat.
- **Sign out** Mi Account, Jika anda saat ini di MIUI ROM.
- **Sign out** semua akun Google untuk menghindari "FRP" (Factory Reset Protection).

## Sebelum memulai Flash LineageOS

1. Pastikan semua syarat diatas sudah terpenuhi, dan semua file yang sudah di download simpan dalam 1 folder, contoh nama folder "LineageOS".

    <details>
       <summary>Picture</summary>
        <p align="center">
          <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/install-los-pict/1-los.png" alt="Picture" width="" height="">
        </p>
    </details>

2. Buka Terminal/CMD, arahkan folder yang tadi kita buat "LineageOS" ke Terminal/CMD.
   - Ketikan perintah: **`cd`** spasi lalu drag & drop folder **LineageOS** ke Terminal/CMD lalu Enter
   - Ketikan **`dir`** Enter


     Jika sudah seperti gambar (contoh) dibawah ini, maka lanjut ke step berikutnya
     <details>
       <summary>Picture</summary>
        <p align="center">
          <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/install-los-pict/2-los.png" alt="Picture" width="" height="">
        </p>
    </details>
3. Jika sudah dipastikan sesuai, lanjut untuk step berikutnya.

## Flash ROM
Silahkan pilih **Basic** kalo kamu masih pemula.
<details>
  <summary>Basic</summary>
 
  Step ini untuk kamu yang masih pemula, pahami baik2 step berikut:
  
  1. Matikan device kamu
  2. Tekan dan tahan tombol **`Power`** + **`Volume Bawah`** sampai adan keterangan **"FASTBOOT"**, lalu hubungkan device ke komputer dengan kabel USB.
  3. Copy - Paste command:
     ```
     fastboot devices
     ```
     Pastikan `Device ID` muncul.
  4. Install Recovery (`recovery.img`)
     Copy - Paste command:
     ```
     fastboot flash recovery recovery.img
     ```
     Tunggu sampai proses install recovery selesai dengan tulisan **"Done"**.
  5. Reboot device ke Recovery Mode
     Tekan dan tahan tombol **`Power` + `Volume Atas`**. Saat Logo "MI" muncul langsung lepaskan tombol **`Power`**.
     <details>
       <summary>Picture</summary>
       <p align="center">
         <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/install-los-pict/los-recovery.png" alt="Picture" width="50%" height="auto">
       </p>
     </details>
  6. Pilih **`Apply update`** ➜ **`Apply from ADB`**
  7. Cek untuk memastikan ADB Sideload terdeteksi di komputer:
     ```
     adb devices
     ```
     Pastikan kembali jika berhasil terdeteksi akan seperti ini:
     ```
     List of devices attached
     fe4afbea        sideload ← terdeteksi
     ```
     <details>
       <summary>Picture</summary>
       <p align="center">
         <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/install-los-pict/sideload.png" alt="Picture" width="" height="">
       </p>
     </details>

     
  8. Install Firmware:
     ```
     adb -d sideload fw.zip
     ```
     Tunggu proses install firmware berjalan, nanti akan muncul keterangan:
     ```
     Signature verification failed
     Install anyway?
     ```
     Pilih: ➜ **YES**

     <details>
       <summary>Picture</summary>
       <p align="center">
         <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/install-los-pict/verifiaction-los.png" alt="Picture" width="50%" height="auto">
       </p>
     </details>

     Proses akan dilanjutkan kembali, dan jika sudah selesai proses install firmware otomatis akan kembali ke menu utama recovery.
10. Pilih **`Advanced`** ➜ **`Reboot to recovery`**.
11. Pilih **`Factory reset`** ➜ **`Format data/factory reset`** ➜ **`Format data`**.  
12. Jika proses Format data selesai, kembali ke menu utama recovery dengan menekan **`←`** yang ada di pojok kiri atas.
13. Pilih **`Apply update`** ➜ **`Apply from ADB`**
14. Kembali ke Terminal/CMD lalu install ROM:
    ```
    adb -d sideload rom.zip
    ```
    Tunggu & pastikan keterangan yang ada di device seperti:
    `Install completed with status 0`
    
    Proses install rom LineageOS **sudah berhasil dan selesai**.
15. Pilih **`Reboot system now`** untuk booting ke LineageOS.

    Jika kamu ingin melakukan install GApps, **Jangan untuk `Reboot system now` tapi lanjut ke step berikutnya**.
16. Kembali ke Terminal/CMD
17. Install GApps

    Di Recovery pilih **`Apply update`** ➜ **`Apply from ADB`**
    ```
    adb -d sideload gapps.zip
    ```
    Tunggu proses install GApps berjalan, nanti akan muncul keterangan:
    ```
    Signature verification failed
    Install anyway?
    ```
    Pilih: **`YES`**

    Proses akan dilanjutkan kembali, dan jika sudah selesai proses install GApps otomatis akan kembali ke menu utama recovery.
18. Pilih **`Factory reset`** ➜ **`Format data/factory reset`** ➜ **`Format data`**.
19. Jika proses Format data selesai, kembali ke menu utama recovery dengan menekan **`←`** yang ada di pojok kiri atas.
20. Pilih **`Reboot system now`** untuk booting ke LineageOS.
21. Selesai!

## Root menggunakan Magisk:
- Reboot ke Recovery Mode
- Di Recovery pilih **`Apply update`** ➜ **`Apply from ADB`**
  ```
  adb -d sideload magisk.zip
  ```
  Tunggu proses install Magisk berjalan, nanti akan muncul keterangan:
  ```
  Signature verification failed
  Install anyway?
  ```
  Pilih: **`YES`**

  Proses akan dilanjutkan kembali, dan jika sudah selesai proses install otomatis akan kembali ke menu utama recovery.
- Pilih **`Reboot system now`** untuk booting ke LineageOS.
- Jika sudah masuk home screen, buka Magisk dan ikutin step2 dari magisk
- Selesai!
</details>

<details>
  <summary>Advance</summary>
  Untuk yang sudah terbiasa install custom rom, ini command untuk install
 
  ```
  adb reboot bootloader
  ```
  ```
  fastboot flash recovery recovery.img
  ```
  ```
  fastboot reboot-recovery
  ```
  ```
  adb -d sideload fw.zip
  ```
  ```
  adb -d sideload rom.zip
  ```
  ```
  adb -d sideload gapps.zip
  ```
  ```
  adb -d sideload magisk.zip
  ```
 
</details>

---
[**← Back**](https://github.com/TriHermawan/RedmiNote10Pro/tree/main?tab=readme-ov-file#install-rom)
