<p align="center">
  <img src="https://github.com/KernelSU-Next/KernelSU-Next/blob/next/assets/kernelsu_next.png" alt="logo" width="96px" height="auto">
</p>

# Run Bank App on Android Root with KernelSU Next

> [!Caution]
> I am not responsible for anything happened to your device do at your own risk!
>
> [`FaultX`](https://t.me/faultx003)

```
Device   : Redmi Note 10 Pro
codename : sweet
ROM      : LineageOS 22.2 Official
```

- Kernel: [KernelSU Next (KSU Next) + SuSFS](https://t.me/venturplayground/62?single) ← _(for LineageOS Official Build)_
- [KernelSU Next](https://github.com/KernelSU-Next/KernelSU-Next/releases/download/v1.0.6/KernelSU_Next_v1.0.6_12490-release.apk) `.apk`

### Required Modules:
- [Zygisk Next](https://github.com/Dr-TSNG/ZygiskNext/releases/latest)
- [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix/releases/latest)
- [Tricky Store](https://github.com/5ec1cff/TrickyStore/releases/latest)
- [Tricky Addon](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases/latest)
- [SUSFS-FOR-KERNELSU](https://github.com/sidex15/susfs4ksu-module)
- [KSU Web UI](https://github.com/5ec1cff/KsuWebUIStandalone/releases/latest) ← Install `.apk`
- [Integrity-Box](https://t.me/MeowRedirect/690)


### Pass Strong Integrity
- Install all the modules in KSU Next.
- Open KSU Next and run:
  - Play Integrity Fix
  
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143821_KernelSU%20Next.png" alt="" width="50%" height="auto">
  - Tricky Store
 
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143821_KernelSU%20Next-2.png" alt="" width="50%" height="auto">
   
- Tap Tricky Store ➜ Click the hamburger menu (three lines) ➜ Tap "**Set Valid Keybox**" ➜ **Save** _(Done! You now pass Strong Integrity)_.

  <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143843_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-143850_KernelSU%20Next.png" alt="" width="50%" height="auto">

### Add VerifiedBootHash (SuSFS)
- Install and Open [KeyAttestation](https://github.com/chiteroman/KeyAttestation/releases)
- Scroll down and copy `VerifiedBootHash`
  
  <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/module/Screenshot_20250520-150344_Key%20Attestation.png" alt="" width="50%" height="auto">

- Paste it to: `/data/adb/VerifiedBootHash/VerifiedBootHash.txt`
- Done!

### App Testing

<img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071800_Key%20Attestation.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071823_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-135213_KernelSU%20Next.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071856_Google%20Play%20Store.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-071926_Google%20Play%20Store.png" alt="" width="50%" height="auto"><img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/bankapps/Screenshot_20250520-134912_Trebuchet.png" alt="" width="50%" height="auto">
 
---
[**← Back**](https://github.com/TriHermawan/RedmiNote10Pro/tree/main?tab=readme-ov-file#run-bank-app-on-android-root-with-kernelsu-next)


 
