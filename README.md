TWRP device configuration for LeEco Le Max 2
==============

kernel source used for prebuilt kernel:
https://github.com/AICP/kernel_motorola_msm8953/

To compile android-9.0 based TWRP
==============

    export ALLOW_MISSING_DEPENDENCIES=true
    . build/envsetup.sh
    lunch omni_sanders-eng && \
    mka adbd recoveryimage 2>&1 | tee make_sanders.log

tee command makes a copy of the terminal output to a file.
If you're using Windows PowerShell? Please relace tee with
Tee-Object

Device configuration for Moto G5S Plus (sanders)
===========================================

The Motorola Moto G5S Plus (codenamed _"sanders"_) is a mid-range smartphone from Motorola mobility.
It was announced on August 2017.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core 2.0 GHz Cortex-A53
Chipset | Qualcomm MSM8953 Snapdragon 625
GPU     | Adreno 506
Memory  | 4 GB RAM
Shipped Android Version | 7.0.0
Storage | 32 GB
MicroSD | Up to 256 GB
Battery | Li-Ion 3000mAh battery
Display | 1080 x 1920 pixels, 5.2 inches (~402 ppi pixel density)
Camera  | Dual 13 MP, f/2.0, autofocus, dual-LED (dual tone) flash, 2150 x 1440 pixels

Copyright 2017 - The LineageOS Project.

![Moto G5S Plus](http://cdn2.gsmarena.com/vv/pics/motorola/motorola-moto-g5s-plus-1.jpg "Moto G5 Plus")
