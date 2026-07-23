# Micro Radar Round TFT

A browser-based firmware installer for the **Micro Radar Round TFT**
project using **ESP Web Tools**. This allows you to flash the firmware
directly from Google Chrome or Microsoft Edge without installing any
desktop flashing software.

## Features

-   Browser-based firmware flashing
-   No desktop flashing software required
-   Powered by ESP Web Tools
-   Hosted on GitHub Pages
-   Simple and beginner-friendly
-   Supports ESP32 WROOM / ESP32 Dev Boards

## Supported Hardware

-   ESP32 WROOM
-   ESP32 Dev Board

## Flash Firmware

Visit the online installer:

**https://lazydayscr.github.io/Micro-Radar-Round-TFT/**

### Installation Steps

1.  Connect your ESP32 using a USB **data** cable.
2.  Open the installer website.
3.  Click **Flash Firmware**.
4.  Select your ESP32 serial port.
5.  Click **Connect**.
6.  Click **Install**.
7.  If your board does not automatically enter download mode, hold the
    **BOOT** button until flashing begins.

## Browser Compatibility

Supported:

-   Google Chrome (Recommended)
-   Microsoft Edge

Not Supported:

-   Firefox
-   Safari

## Firmware Layout

  File             Offset
  ---------------- ---------
  bootloader.bin   0x1000
  partitions.bin   0x8000
  boot_app0.bin    0xe000
  firmware.bin     0x10000

## Credits

### Original Project

**Anthony Sturdy**

Source Code:

https://github.com/AnthonySturdy/micro-radar

### Browser Firmware Installer

Developed by **LazyDays Creation**

This repository provides a browser-based firmware installation interface
using **ESP Web Tools** for the original project.

## License

The original **Micro Radar** project is licensed under the **MIT
License**.

Copyright (c) 2026 Anthony Sturdy

This repository includes only the web-based firmware installer and does
not claim ownership of the original firmware or project.

Please retain the original copyright and license notices when
redistributing the firmware or source code.

See the included **LICENSE** file for the full MIT License text.

## Disclaimer

Use this firmware at your own risk.

Always ensure the firmware is intended for your specific ESP32 hardware
before flashing.
