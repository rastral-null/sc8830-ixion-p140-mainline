# Spreadtrum SC8830/DEXP Ixion P140 mainlining repository

Out-of-tree patches, Device Tree sources, and BootROM tools for bringing up mainline Linux on the DEXP Ixion P140 (`sprd,sp8835eb` reference board) and other Spreadtrum SC8830 devices, with the goal of upstreaming support into the mainline kernel.
<img width="261" height="500" alt="image" src="https://github.com/user-attachments/assets/bc2d06d3-e16e-4258-bd11-28b3a6afbd56" />

## Similar Devices
Samsung Galaxy J1 (SM-J100H / SM-J120H), Galaxy J1 Mini (SM-J105H), Samsung Galaxy Core Prime (SM-G360H), Galaxy Grand Prime VE (SM-G531H), DEXP Ixion P145, DEXP Ixion P4, and Ginzzu RS7D are the closest hardware-compatible devices.

## Hardware Specifications for P140

| Component | Details |
| :--- | :--- |
| **SoC** | Spreadtrum SC8830 (Quad-core ARM Cortex-A7 @ 1.2 GHz) |
| **Board / Reference** | DEXP Ixion P140 (`sprd,sp8835eb`) |
| **RAM** | 1 GiB (`0x80000000` – `0xc0000000`) |
| **Display** | 480×854 MIPI-DSI (`simple-framebuffer` @ `0x9f82d000`) |
| **Touchscreen** | Silead GSLx680 (`i2c4`) |
| **Sensors** | mCube MC3xxx accelerometer, MEMSIC MMC3524 magnetometer, Dyna Image AP3212C ALS/PS (`i2c2`) |
| **PMIC / Charger** | Spreadtrum SC2713 / ADI bus (`0x40030000`), Fairchild FAN5405 charger |
| **BootROM USB ID** | `1782:4d00` (Spreadtrum HDLC + CRC16 protocol) |

## License

This project is licensed under GPL-2.0-only (Device Tree files are dual-licensed under (GPL-2.0-only OR MIT).

Warning! This project is using AI code. If you don't like it, don't use it
