---
title: MIUI
parent: Flashing
nav_order: 2
---

# MIUI

### Install Stock ROM MIUI via OrangeFox  

- [OrangeFox R11.1_6 MIUI](https://github.com/basamaryan/android_device_xiaomi_sweet-TWRP/releases/download/R11.1_6/OrangeFox-R11.1_6-Unofficial-sweet-MIUI.zip)

- Flash [ROM OFFICIAL MIUI](../rom/miui.md) (type: RECOVERY - `.zip`)

- Format Data ➜ **"YES"**

- Reboot System

---

### Install Stock ROM MIUI via MiFlash


1. **Download Fastboot ROM resmi**  
Cari ROM model:  
sweet (Global/EEA/Indonesia) →  [Download](../rom/1-miui.md) _(Format file harus `.tgz`)_ lalu extract
  
2. **Masuk mode Fastboot**
    - Matikan HP
    - Tekan Volume Down + Power
    - Akan muncul logo fastboot
    
3. Jalankan MiFlash  
    - Buka aplikasi **Xiaomi MiFlash Tool**  
    - Klik **Select** → arahkan ke folder Fastboot ROM (folder yang berisi images)  
    - Pastikan tipe flash di bawah dipilih:  
      - **✔ clean all**  (Data akan terhapus!) 
4. **Klik Flash**
Tunggu proses selesai hingga:  
`Flash done`  