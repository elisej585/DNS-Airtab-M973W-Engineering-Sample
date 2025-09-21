DNS Airtab M973W Engineering Sample (Prototype)
https://img.shields.io/badge/License-MIT-yellow.svg

This repository contains hardware specifications and firmware dumps for the DNS Airtab M973W Engineering Sample (Prototype). This device is a pre-production engineering sample based on the Rockchip RK3066 platform.

⚠️ Disclaimer
This device is an engineering sample. Its hardware and software are unstable, not finalized, and are intended for development and testing purposes only. Use this information at your own risk.

Firmware backup is located here: https://drive.google.com/drive/folders/1n0FV64SBxIvUxBhyOcANfHTxzBduREGI?dmr=1&ec=wgc-drive-hero-goto

backup.img - Backup partition

boot.img - Android boot partition

cache.img - Cache partition

kernel.img - Linux kernel image

kpanic.img - Kernel panic storage partition

loader.bin - Initial bootloader

misc.img - Miscellaneous system partition

parameter.txt - Device parameters and partition table

recovery.img - Android recovery partition

system.img - Android system partition

userdata.img - User data partition

📋 Hardware Specifications
SoC: Rockchip RK3066 (Dual-Core Cortex-A9 @ 1.6GHz, Mali-400 MP4)

RAM: 1GB DDR3

Storage: 16GB Hynix eMMC

Display: RK30 LCDC controller with dual display support (LCDC0 and LCDC1)

Touchscreen: FocalTech FT5x0X capacitive touchscreen controller

Cameras: Hynix Hi253 (Rear), Hynix Hi704 (Front), GalaxyCore GC0308 (Front secondary)

Audio Codec: Realtek RT5631

PMIC: X-Powers AXP202 power management integrated circuit

Sensors: 
- MMA7660 3-axis accelerometer
- AKM8975 compass/magnetometer (probe failed)
- L3G4200D gyroscope (probe failed) 
- CM3217 ambient light sensor (probe failed)

Connectivity: 
- Custom Rockchip Wi-Fi/BT module (RK29 SDK)
- Bluetooth RFKILL controller
- USB 2.0 OTG and Host support (DWC OTG controller)
- Multiple I2C buses for peripheral communication

Real-Time Clock: HYM8563 RTC module

IR Remote: Infrared remote control support (LIRC)

PCB Revision: M830R TV3.0

Storage Controller: RK30xx NAND flash controller with FTL support

💾 Firmware Information
Android Version: 4.1.1 (Jelly Bean)

Kernel Version: 3.0.8+

Bootloader Version: 2012-12-07#1.22

Build Date: Wed Jul 3 14:27:22 CST 2013

Dump Date: 2025-09-21

Dump Method: rkdeveloptool on Arch Linux

System Features:
- Android USB gadget support (Mass Storage Function)
- VPN support (PPTP, PPP, MPPE)
- Netfilter and IP tables
- EXT4 filesystem support
- Android logging system (logcat)
- FUSE filesystem support
- Interactive governor for CPU frequency scaling
- Hardware video acceleration (RGA driver)

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

👤 Author
elisej585

Github: https://github.com/elisej585
