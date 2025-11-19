---
title: Unlock Bootloader
parent: Bootloader
nav_order: 1
---
# Unlock Bootloader

Unlock bootloader (UBL) memungkinkan kamu memasang custom ROM, root, dan modifikasi.
Namun, melakukan UBL akan menghapus semua data, jadi pastikan kamu sudah backup.  

{: .warning }
> Peringatan & Resiko
> 
> - Semua data akan terhapus (factory reset)
> - Garansi mungkin tidak berlaku tergantung kebijakan toko
> - Risiko bootloop jika langkah salah
> - Beberapa aplikasi (perbankan, e-wallet, dll.) mungkin mendeteksi status bootloader terbuka.  

Lanjutkan jika kamu paham konsekuensinya.


## ✅ Persiapan  
Sebelum mulai, pastikan kamu sudah:
1. Menggunakan akun Mi yang aktif
Login di HP:  
Settings → Mi Account
2. Mengaktifkan mode pengembang.  
Settings → About phone
Tap MIUI Version 7–10 kali hingga muncul _“You are now a developer!”_
3. Mengaktifkan OEM Unlocking & USB Debugging
Masuk ke:
Settings → Additional settings → Developer options
Aktifkan:
- ✔ OEM unlocking
- ✔ USB debugging
- ✔ USB debugging (security settings) → login akun Mi

4. Menghubungkan akun Mi ke status Mi Unlock
Masuk:  
Settings → Additional settings → Developer options → Mi Unlock status.  
Lalu pilih:  
➡ Add account and device.  
Jika berhasil akan muncul:
_"Added successfully"_

## 🖥️ Langkah di PC (Windows)
1. Download alat UBL  
Download di situs resmi:
[Mi Unlock Tool](https://en.miui.com/unlock/download_en.html) (MiFlash Unlock)  
(Biasanya berupa file ZIP)  
Ekstrak → jalankan miflash_unlock.exe  

2. Masuk ke mode Fastboot
Di HP:
- Matikan perangkat
- Tekan Volume Down + Power bersamaan
- Muncul logo kelinci + tulisan fastboot
- Kemudian colokkan ke PC.

## 🚀 Proses Unlock
1. Login Mi Unlock Tool  
Gunakan akun Mi yang sama seperti di HP.
2. Tunggu pengecekan  
Jika semua benar, akan muncul tombol Unlock.
3. Klik Unlock  
Biasanya muncul status:  
- 0 hours (langsung unlock)
- 72 hours (3 hari menunggu)
- 168 hours (7 hari menunggu)  

Jika disuruh menunggu:  
> “Please unlock after XXX hours”  

Cukup biarkan HP online & jangan logout Mi Account selama masa tunggu.  

4. Selesaikan proses unlock  
Setelah jam tunggu selesai, ulangi langkah dan klik Unlock anyway.  
HP akan reboot → factory reset → bootloader terbuka.  

## 🎉 Konfirmasi Bootloader Sudah Terbuka
Masuk fastboot lalu di PC jalankan:
```
fastboot oem device-info
```
Jika muncul:
```
Device unlocked: true
```

Berarti UBL sukses.

