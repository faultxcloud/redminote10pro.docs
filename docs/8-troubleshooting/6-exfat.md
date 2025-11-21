---
title: exFAT
parent: Troubleshooting
nav_order: 6
---

# exFAT
**exFAT** _(Extended File Allocation Table)_ adalah sistem file yang dikembangkan oleh Microsoft khusus untuk media penyimpanan flash seperti SD Card dan USB flash drive. exFAT dirancang sebagai pengganti modern dari FAT32.

Tujuan utama diciptakannya exFAT adalah untuk mengatasi keterbatasan serius pada FAT32, terutama batas ukuran file dan ukuran drive (partisi). Karena exFAT tidak memiliki batasan ukuran file 4GB, ini menjadikannya pilihan ideal untuk kartu SD besar (64GB ke atas) yang digunakan untuk menyimpan video resolusi tinggi (4K/8K).

| **Tipe**          | **FAT32**                       | **exFAT**                             |
| :----------------- | :------------------------------- | :------------------------------------- |
| Maks. ukuran file | 4 GB                            | Hampir tanpa batas                    |
| Maks. kapasitas   | ±2 TB                           | Sangat besar (PB/EB)                  |
| Kompatibilitas    | Sangat luas                     | Luas, tapi tidak semua perangkat lama |
| Kecepatan         | Standar                         | Lebih cepat untuk file besar          |
| Cocok untuk       | Perangkat lama, flashdisk kecil | SD card besar, flashdisk modern, SSD  |

---

# exFAT - SDcard

Cara merubah format SDCard `FAT32` ke `exFAT` menggunakan custom recovery _OrangeFox_.

{: .warning }
> Pastikan DATA penting kamu yang di SDCard sudah di **BACKUP!**. Karena proses ini akan mengapus total isi DATA yang ada di SDCard kamu.  
>
> Saya tidak bertanggung jawab atas apapun yang terjadi pada perangkat kamu, lakukan dengan risiko kamu sendiri!

Perhatikan step by step dengan teliti..  

![](../assets/images/exfat/1.png)  

![](../assets/images/exfat/2.png)  

![](../assets/images/exfat/3.png)  

![](../assets/images/exfat/4.png)  
