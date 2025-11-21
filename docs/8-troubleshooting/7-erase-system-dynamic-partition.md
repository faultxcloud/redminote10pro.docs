---
title: Erase System Dynamic Partition
parent: Troubleshooting
nav_order: 7
---

# Erase System Dynamic Partition

Beberapa user mengalami freeze di custom ROM base AOSP, dan solusinya adalah _Erase System Dynamic Partition_.  
Lalu Flash ulang ROM AOSP.  

{: .warning }
> I am not responsible for anything happened to your device do at your own risk!
>
> Saya tidak bertanggung jawab atas apapun yang terjadi pada perangkat Anda, lakukan dengan risiko Anda sendiri!  

- Step to Erase System Dynamic Partition
    - Reboot to custom recovery (TWRP/Orangefox)

- Run this command (cmd-windows/macOS/Linux):
    1. `fastboot erase vendor`
    2. `fastboot erase system`

