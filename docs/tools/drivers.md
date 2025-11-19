---
title: Driver
parent: Tools
nav_order: 1
---
# Install Driver

<!--
<details>
  <summary></summary>
  <p align="center">
    <img src="" alt="Picture" width="" height="">
  </p>
</details>
-->

# Install adb & fastboot Driver

{: .note }
> Attention to the installation steps properly

### Step 1  

Download & extract:
  
  - [ADB (Windows)](https://cloud03.faultx.workers.dev/1:/ADB%20Fastboot/adb-setup-1.4.3.zip?a=view)
  - [Mi Unlock Tools](https://cloud03.faultx.workers.dev/1:/Mi%20Unlock/miflash_unlock_en_7.6.727.43.zip?a=view)

  <p align="center">
    <img src="../assets/images/adb-fastboot/1.png" alt="Picture" width="" height="">
  </p>


### Step 2
  
Double click ➜ `adb-setup-1.4.3.exe`  
Then press the key ➜ **Y**  
_See the image below_
  <p align="center">
    <img src="../assets/images/adb-fastboot/2.png" alt="Picture" width="" height="">
  </p>


### Step 3
Make sure ➜ ☑️ _Always trust software from "Gooogle Inc"_ , Then click **"Install"**
  <p align="center">
    <img src="../assets/images/adb-fastboot/3.png" alt="Picture" width="" height="">
  </p>

### Step 4
Click ➜ **Next**
  <p align="center">
    <img src="../assets/images/adb-fastboot/4.png" alt="Picture" width="" height="">
  </p>


#### Step 5
The message "Ready to use" will appear.
Click **"Finish"** 
  <p align="center">
    <img src="../assets/images/adb-fastboot/5.png" alt="Picture" width="" height="">
  </p>

### Step 6
Double click `miflash_unlock.exe`
  <p align="center">
    <img src="../assets/images/adb-fastboot/6.png" alt="Picture" width="" height="">
  </p>

#### Step 7
  <p align="center">
    <img src="../assets/images/adb-fastboot/7.jpeg" alt="Picture" width="" height="">
  </p>

### Step 8
Click the **"Gear"** icon (see the red circle)
  <p align="center">
    <img src="../assets/images/adb-fastboot/8.png" alt="Picture" width="" height="">
  </p>

### Step 9</summary>
- Open **Device Manager** (Click the **Start** button (Windows logo) ➜ Type **Device Manager** in the search bar ➜ Click on the **Device Manager** result)
- Connect your device to the computer via USB cable
- If Device Manager shows **`⚠︎ Android`** it means the fastboot driver has not been installed correctly
- Click ➜ **Check** _"Click the button to install drive"_
  <p align="center">
    <img src="../assets/images/adb-fastboot/9.png" alt="Picture" width="" height="">
  </p>

### Step 10
- If it says **"Connect your device again"**, unplug the USB and reconnect your device to the computer
- The driver should then install automatically
  <p align="center">
    <img src="../assets/images/adb-fastboot/10.png" alt="Picture" width="" height="">
  </p>

### Step 11
If the installation is successful, the display will look like the image below.  

Then **Close** `Mi Unlock`.
  <p align="center">
    <img src="../assets/images/adb-fastboot/11.png" alt="Picture" width="" height="">
  </p>

### Step 12
- Open Terminal / CMD
- Type the command: `fastboot devices`  

If the result looks like this, you're done.
  <p align="center">
    <img src="../assets/images/adb-fastboot/12.png" alt="Picture" width="" height="">
  </p>
