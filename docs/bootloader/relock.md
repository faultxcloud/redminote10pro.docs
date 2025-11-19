---
title: Relock Bootloader
parent: Bootloader
nav_order: 2
---
# Relock Bootloader
Relock bootloader dilakukan ketika kamu ingin mengembalikan ke kondisi pabrik, biasanya sebelum dijual atau saat ingin memulihkan keamanan perangkat.  

{: .highlight}
> Relock hanya boleh dilakukan jika HP memakai ROM resmi (MIUI Oficial / Stock ROM) yang tidak dimodifikasi, non-root, dan partisi lengkap.
Jika kamu relock saat memakai Custom ROM → 100% brick (bootloop / hardbrick).

## ⚠️ Risiko Relock Bootloader
- HP akan factory reset
- Jika ROM bukan ROM resmi → bootloop / brick
- Semua data di storage akan dihapus

## ✅ Syarat Wajib Sebelum Relock
1. **Harus memakai ROM Resmi / Stock ROM**  
Boleh:  
MIUI Global / EEA / Indonesia resmi
Fastboot ROM resmi (diinstall via MiFlash)  
Tidak boleh:  
Custom ROM (PixelOS, LineageOS, dll.)
ROM yang sudah di-root
ROM modifikasi/patched. 
2. **Tidak boleh ada Magisk / Root / Modifikasi**  
Pastikan:
    - Tidak ada Magisk
    - Tidak ada TWRP (bisa tapi tidak disarankan)
    - Boot image tidak dipatch
3. **Disarankan install ulang menggunakan Fastboot ROM**  
Gunakan MiFlash dengan opsi:  
**clean all** (aman)  
atau  
**clean all and lock** (langsung relock secara otomatis)

## 🖥️ ReLock Bootloader via MiFlash
Ini adalah cara paling aman untuk relock bootloader di Redmi Note 10 Pro.
1. **Download Fastboot ROM resmi**  
Cari ROM model:  
sweet (Global/EEA/Indonesia) →  [Download](https://faultxcloud.github.io/redminote10pro.docs/rom/miui.html)  
Format file harus `.tgz`.
2. **Masuk mode Fastboot**
    - Matikan HP
    - Tekan Volume Down + Power
    - Akan muncul logo fastboot
3. Jalankan MiFlash  
    - Buka aplikasi **Xiaomi MiFlash Tool**  
    - Klik **Select** → arahkan ke folder Fastboot ROM (folder yang berisi images)  
    - Pastikan tipe flash di bawah dipilih:  
Opsi untuk relock aman:  
        - **✔ clean all and lock**  
4. **Klik Flash**
Tunggu proses selesai hingga:  
`Flash done`  
HP akan reboot otomatis dan status bootloader terkunci.

