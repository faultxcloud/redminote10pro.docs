---
title: Install Custom Recovery
parent: Recovery
nav_order: 1
---

# Install Custom Recovery di MIUI (Permanen)

Pastikan komputer Anda sudah terpasang [adb-fastboot](../tools/adb-fastboot.md) (driver) dengan benar.  

1. **Download**  
[TWRP](https://dl.twrp.me/sweet/twrp-3.7.1_12-0-sweet.img) `(.img)`   
[OrangeFox-MIUI](https://github.com/basamaryan/android_device_xiaomi_sweet-TWRP/releases/download/R11.1_6/OrangeFox-R11.1_6-Unofficial-sweet-MIUI.zip) `(.zip)` ➜ Simpan ke SDCard Anda  

2. **Matikan Device**  
Masuk ke fastboot mode dengan menekan dan menahan tombol **Power** + **Volume Down** secara bersamaan. Tetap tahan hingga masuk ke mode fastboot, lalu lepaskan.

3. **Setelah berada di fastboot mode**  
Hubungkan ponsel ke PC menggunakan kabel USB.

4. **Buka CMD**  
ketik perintah berikut:  
    ```
    fastboot devices
    ```
    Lalu tekan Enter.  

    Pastikan ID perangkat Anda muncul — itu berarti perangkat terdeteksi.   
    Jika tidak terdeteksi, Anda perlu menginstal ulang driver adb-fastboot dengan benar.  

5. **Install TWRP**  
Gunakan perintah:  
`fastboot flash recovery` (drag & drop file twrp .img di sini)  
lalu tekan Enter  

    Contoh:  
    `fastboot flash recovery twrp-3.7.1_12-0-sweet.img`  

6. **Reboot**  
Reboot device ke _Recovery Mode_ dengan menekan dan menahan tombol:  
   - **Power** + **Volume Up**   

   Saat logo “MI” muncul, segera lepaskan tombol **Power**.
7. Setelah masuk ke TWRP  
flash file `OrangeFox (.zip)` yang sudah Anda simpan di SDCard. lalu install sampai selesai dan akan otomatis reboot ke Recovery

8. Selesai!