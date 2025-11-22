---
title: Home
nav_order: 1
---

![](assets/images/fx-sweet1.png)
# Redmi Note 10 Pro • Documentation

```
Device   : Redmi Note 10 Pro
Codename : sweet
----------------------------------
Device   : Redmi Note 10 Pro Max
Codename : sweetin
Region   : India
```

<span class="fs-1">
[<img src="{{ '/assets/icons/telegram.svg' | relative_url }}" width="16" style="vertical-align:middle;"> Telegram](https://t.me/faultx003){: .btn }
</span>
<span class="fs-1">
[<img src="{{ '/assets/icons/web.png' | relative_url }}" width="16" style="vertical-align:middle;"> Link](https://linktr.ee/faultx.repair){: .btn }
</span>
<span class="fs-1">
[<img src="{{ '/assets/icons/g-cloud-icon.png' | relative_url }}" width="16" style="vertical-align:middle;"> Cloud](https://cloud03.faultx.workers.dev/){: .btn }
</span>


{: .warning }
> _I am not responsible for anything happened to your device do at your own risk!_
>
> Saya tidak bertanggung jawab atas apapun yang terjadi pada perangkat Anda, lakukan dengan risiko Anda sendiri!


Beberapa panduan di sini mungkin terlihat sederhana, tetapi sebenarnya melibatkan perubahan besar pada sistem, seperti membuka kunci bootloader, memasang recovery kustom, flashing ROM, atau melakukan root.  

Semua proses ini aman jika dilakukan dengan benar, namun tetap memiliki risiko yang penting untuk kamu ketahui.

 **Hal-hal penting sebelum mulai:**

- **Bootloop / perangkat tidak bisa masuk sistem:**  
Jika salah memilih file atau langkahnya tidak tepat, hp bisa stuck di logo atau tidak bisa masuk sistem.

- **TEE Broken (Trusted Execution Environment):**  
Kesalahan flashing bisa merusak modul keamanan bawaan hp. Dampaknya bisa berupa:  
    - Widevine turun ke L3 (kualitas streaming jadi lebih rendah)  
    - Play Integrity gagal (beberapa aplikasi menganggap perangkat tidak aman)  
    - Sensor sidik jari atau Face Unlock jadi tidak stabil  
    - Sangat berbahaya untuk melakukan *relock* bootloader

- **Privasi & aplikasi perbankan:**  
Perubahan pada sistem seperti root, custom ROM, atau TEE yang rusak dapat membuat aplikasi seperti:  
   - Mobile banking  
   - E-wallet (Dana, OVO, Gopay, ShopeePay)  
   - Aplikasi kantor/kerja yang memakai keamanan tinggi  
   mendeteksi perangkat sebagai "tidak aman" dan menolak untuk dibuka.

 - **Keamanan data pribadi:**  
   Memodifikasi sistem bisa membuka potensi celah keamanan. Pastikan file yang digunakan berasal dari sumber terpercaya.  
   Jika salah flashing, perangkat bisa masuk kondisi yang membuat data personal tidak bisa dipulihkan.

 - **Relock Bootloader:**  
   Jangan mengunci kembali bootloader jika perangkat tidak benar-benar *stock*. Ini bisa menyebabkan kerusakan permanen.

 - **Backup itu wajib:**  
   Banyak proses akan menghapus data internal. Cadangkan semua data penting sebelum mulai.

 Panduan ini dibuat agar kamu bisa melakukan semuanya dengan aman.  
 Baca langkah-langkah dengan teliti, gunakan file yang tepat untuk *Redmi Note 10 Pro (sweet/sweetin)*, dan jangan terburu-buru.

 [`FaultX`](https://t.me/faultx003)