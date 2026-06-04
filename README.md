# DOOM Watch

> Play classic DOOM on an ESP32 AMOLED smartwatch with touch controls, motion controls, audio, battery monitoring, and WAD management.

![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Display](https://img.shields.io/badge/Display-AMOLED-green)
![Engine](https://img.shields.io/badge/Engine-DoomGeneric-red)

## Support / Get It

If you like this project, you can support me on [Ko-fi](https://ko-fi.com/s/c68a796d12) ☕

# Picker
![Watch UI](IMG1.jpg)

## Features
- Classic DOOM gameplay using DoomGeneric
- IWAD and PWAD support
- Custom WAD launcher
- Per-WAD save folders (auto-created)
- Touch drag joystick
- Physical button controls
- ES8311 **SFX support only** (audio playback can be added if requested)
- AXP2101 battery HUD
- Adjustable volume, brightness, battery HUD, and control sensitivity
- IMU wrist-tilt motion controls
- Save-name macro for quick saves

# Demo
![Watch UI](15607.gif)
![Watch UI](15608.gif)
![Watch UI](15609.gif)

## Hardware
Tested hardware: [ESP32-S3 Touch AMOLED 2.06](https://www.waveshare.com/wiki/ESP32-S3-Touch-AMOLED-2.06)

## Controls

| Action | Control |
|---|---|
| Move forward/back | Touch drag up/down |
| Turn left/right | Touch drag left/right |
| Fire / Select | BOOT button |
| Use / Open | Top-right screen tap |
| Weapon cycle | Top-left screen tap |
| Menu / Back | PWR button |
| Auto save-name | BOOT + PWR |

## Required Libraries
- Arduino_GFX_Library
- Arduino_DriveBus_Library
- ESP_I2S
- XPowersLib
- Preferences
- SD_MMC
- DoomGeneric

## DoomGeneric Setup
Need help? Text me on (https://www.instagram.com/tsixom)


