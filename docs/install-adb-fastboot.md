<!--
<details>
  <summary></summary>
  <p align="center">
    <img src="" alt="Picture" width="" height="">
  </p>
</details>
-->

# Install adb & fastboot Driver

> [!NOTE]
> Attention to the installation steps properly

<details>
  <summary>Step 1</summary>
  Download & extract:
  
  - [ADB (Windows)](https://cloud03.faultx.workers.dev/1:/ADB%20Fastboot/adb-setup-1.4.3.zip?a=view)
  - [Mi Unlock Tools](https://cloud03.faultx.workers.dev/1:/Mi%20Unlock/miflash_unlock_en_7.6.727.43.zip?a=view)
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/1.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 2</summary>
  
  
  
  Double click ➜ `adb-setup-1.4.3.exe`

  Then press the key ➜ **Y**

  _See the image below_
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/2.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 3</summary>
  
  
  
  Make sure ➜ ☑️ _Always trust software from "Gooogle Inc"_ , Then click **"Install"**
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/3.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 4</summary>


  Click ➜ **Next**
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/4.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 5</summary>

  The message "Ready to use" will appear.

  Click **"Finish"** 
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/5.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 6</summary>


  Double click `miflash_unlock.exe`
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/6.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 7</summary>
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/7.jpeg" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 8</summary>

  Click the **"Gear"** icon (see the red circle)
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/8.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 9</summary>

  
  - Open **Device Manager** (Click the **Start** button (Windows logo) ➜ Type **Device Manager** in the search bar ➜ Click on the **Device Manager** result)
  - Connect your device to the computer via USB cable
  - If Device Manager shows **`⚠︎ Android`** it means the fastboot driver has not been installed correctly
  - Click ➜ **Check** _"Click the button to install drive"_
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/9.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 10</summary>

  - If it says **"Connect your device again"**, unplug the USB and reconnect your device to the computer
  - The driver should then install automatically
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/10.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 11</summary>

  If the installation is successful, the display will look like the image below.

  Then **Close** `Mi Unlock`.
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/11.png" alt="Picture" width="" height="">
  </p>
</details>
<details>
  <summary>Step 12</summary>


  - Open Terminal / CMD
  - Type the command: `fastboot devices`

If the result looks like this, you're done.
  <p align="center">
    <img src="https://github.com/TriHermawan/RedmiNote10Pro/blob/main/assets/adb-fastboot-pict/12.png" alt="Picture" width="" height="">
  </p>
</details>

---

[**← Back**](https://github.com/TriHermawan/RedmiNote10Pro/tree/main?tab=readme-ov-file#adb--fastboot)
