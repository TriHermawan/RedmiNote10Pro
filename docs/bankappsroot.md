<!-- <p align="center">
  <img src="https://github.com/KernelSU-Next/KernelSU-Next/blob/next/assets/kernelsu_next.png" alt="logo" width="96px" height="auto">
</p> -->

# Run Bank App on Android Root

> [!Caution]
> I am not responsible for anything happened to your device do at your own risk!
>
> [`FaultX`](https://t.me/faultx003)

```
Device   : Redmi Note 10 Pro
codename : sweet
```

### Test ROM

| ROM Name | Android | Kernel |
|-|:-:|-|
| LineageOS 22.2 OFFICIAL | 15 | [LOSPerf + KSUNext + SUSFS](https://t.me/venturplayground) |
| PixelOS OFFICIAL | 15 | [Vantom KSU Next](https://t.me/venturplayground) |

Root
- [KernelSU Next](https://github.com/KernelSU-Next/KernelSU-Next/releases/download/v1.0.7/KernelSU_Next_v1.0.7_12602-release.apk) `.apk`
<!-- - [Magisk](https://github.com/topjohnwu/Magisk/releases/download/v29.0/Magisk-v29.0.apk) -->

### Root Detection Apps

| App Name | Link |
|-|-|
| Momo | [Download](https://t.me/faultx003/140)
| KeyAttestation (forked) | [Download](https://github.com/chiteroman/KeyAttestation/releases)

### Required Modules:

- [ReZygisk](https://github.com/PerformanC/ReZygisk/releases/download/v1.0.0-rc.2/ReZygisk-v1.0.0-rc.2-release.zip) (LineageOS) | [Zygisk Next](https://github.com/Dr-TSNG/ZygiskNext/releases/download/v1.2.8/Zygisk-Next-1.2.8-512-4b5d6ad-release.zip) (PixelOS)
- [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix/releases/latest) (LineageOS) | [Play Integrity Fork](https://github.com/osm0sis/PlayIntegrityFork/releases) (PixelOS)
- [Tricky Store](https://github.com/5ec1cff/TrickyStore/releases/latest)
- [Tricky Addon](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases/latest)

<!--
- [ReZygisk](https://github.com/PerformanC/ReZygisk/releases/download/v1.0.0-rc.2/ReZygisk-v1.0.0-rc.2-release.zip)
- [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix/releases/latest)
- [Tricky Store](https://github.com/5ec1cff/TrickyStore/releases/latest)
- [SUSFS-FOR-KERNELSU](https://github.com/sidex15/susfs4ksu-module)
- [Integrity-Box](https://t.me/MeowRedirect/690)
-->

<!--
- [Zygisk Next](https://github.com/Dr-TSNG/ZygiskNext/releases/latest)
- [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix/releases/latest)
- [Tricky Store](https://github.com/5ec1cff/TrickyStore/releases/latest)
- [Tricky Addon](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases/latest)
- [SUSFS-FOR-KERNELSU](https://github.com/sidex15/susfs4ksu-module)
- [KSU Web UI](https://github.com/5ec1cff/KsuWebUIStandalone/releases/latest) ← Install `.apk`
- [Integrity-Box](https://t.me/MeowRedirect/690)
-->

### Step

> [!Note]
> If you want (MEETS STRONG INTEGRITY) find a `keybox.xml` that has not been revoked. import `keybox.xml` in TrickyStore > Set Custom Keybox > find the `keybox.xml` that you got > save.
>

1. Install Module:
   - Install ReZygisk / Zygisk Next
   - Install Play Integrity Fix / Play Integrity Fork
   - Tricky Store
   - Reboot
   - Install Tricky Addon
   - Reboot
2. Open KSU Next, Run Play Integrity Fix

   <!-- <details>
     <summary>Screenshot</summary>
     <img src="" alt="" width="50%" height="auto">
   </details> -->

   <details>
     <summary>Screenshot</summary>
     <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250523-100318_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250523-100418_KernelSU%20Next.png" alt="" width="50%" height="auto">
   </details>

3. Run Tricky Store ➜ Click the hamburger menu (three lines)
   <details>
     <summary>Screenshot</summary>
     <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250523-100427_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250523-100433_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250523-100448_KernelSU%20Next.png" alt="" width="50%" height="auto">
   </details>

4. Clear Data PlayStore
   <details>
     <summary>Screenshot</summary>
     <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250523-085303_Settings.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250522-150607_Play%20Integrity%20API%20Checker.png" alt="" width="50%" height="auto">
   </details>

<!--
### Pass Strong Integrity
- Install all the modules in KSU Next.
- Open KSU Next and run:
  - Play Integrity Fix
  
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143821_KernelSU%20Next.png" alt="" width="50%" height="auto">
  - Tricky Store
 
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143821_KernelSU%20Next-2.png" alt="" width="50%" height="auto">
   
- Tap Tricky Store ➜ Click the hamburger menu (three lines) ➜ Tap "**Set Valid Keybox**" ➜ **Save** _(Done! You now pass Strong Integrity)_.

  <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143843_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143850_KernelSU%20Next.png" alt="" width="50%" height="auto"> -->

<!-- 
### Add VerifiedBootHash (SuSFS)
- Install and Open [KeyAttestation](https://github.com/chiteroman/KeyAttestation/releases)
- Scroll down and copy `VerifiedBootHash`
  
  <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-150344_Key%20Attestation.png" alt="" width="50%" height="auto">

- Paste it to: `/data/adb/VerifiedBootHash/VerifiedBootHash.txt`
- Done! -->

<!--
### App Testing

<details>
  <summary>Screenshot</summary>
  <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071800_Key%20Attestation.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071823_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-135213_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071856_Google%20Play%20Store.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071926_Google%20Play%20Store.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-134912_Trebuchet.png" alt="" width="50%" height="auto">
</details> -->

 
---
[**← Back**](https://github.com/TriHermawan/RedmiNote10Pro/tree/main?tab=readme-ov-file#run-bank-app-on-android-root)


 
