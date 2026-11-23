# ATS Mini V4B Firmware

Custom firmware for the **ATS Mini V4B (16 MB flash)** with ESP32-S3 and Si4732.
Version **2026.11.0**. Built with ESPHome.

## Features
- FM, LW, MW and SW (2.3-26.1 MHz) with AM, LSB, USB and CW
- FT8 receiver on 9 bands with country, distance and bearing
- RDS, LW/MW/SW station names with UTC schedules, Sri Lankan FM names
- 60 favourites, DX log, Scan & Store, band scope
- 4 themes, quiet mode, battery protection
- Home Assistant (ESPHome), web page, hotspot, OTA update
- One-knob control

## Files
| File | Use |
|---|---|
| `1st.bin` | Full factory image. Flash at address 0x0 over USB. |
| `1st.ota.bin` | Update file. Upload it on the radio's web page. |
| `ATS_Mini_V4B_User_Guide.pdf` | User guide |

## Install (USB)
