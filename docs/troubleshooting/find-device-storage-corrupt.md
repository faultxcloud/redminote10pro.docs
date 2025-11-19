---
title: Find Device storage corrupt
nav_order: 2
has_children: true
---

# Fix "Find Device storage corrupt. Your device is unsafe now""

{: .caution }
> Do With Your Own Risk!!

### Metode 1

1. Flash [Orangefox R11.1_3](https://onboardcloud.dl.sourceforge.net/project/orangefox-releases/sweet/04122023/OrangeFox-R11.1_3-Unofficial-sweet.zip)
2. Flash [PixelOS A12](https://cloud03.faultx.workers.dev/0:/PixelOS_sweet-12.1-20220812-0031.zip?a=view)  
    - Flash ROM PixelOS
    - Format data ➜ YES
    - Reboot system  

4. Flash [ROM MIUI 13/14](../rom/miui.md) Type: `Recovery`
    - Flash ROM MIUI
    - Format data ➜ YES
    - Reboot system
5. Done!

---

### Metode 2


{: .note }
> Root Required, Testing from AOSP 14 to MIUI


Sebelum flash MIUI ROM:
- Hapus semua isi folder **"fdsd"** _(Gunakan file manager seperti MT Mnanager atau sejenisnya)_  
    ```
    mnt/vendor/persist/fdsd
    ```
- Reboot system
- Reboot ke TWRP/OrangeFox
- Flash MIUI ROM
- Done!