# DOOM Watch

> Play classic DOOM on an ESP32 AMOLED smartwatch with touch controls, motion controls, audio, battery monitoring, and WAD management.

![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Display](https://img.shields.io/badge/Display-AMOLED-green)
![Engine](https://img.shields.io/badge/Engine-DoomGeneric-red)

# Picker
![Watch UI](IMG1.jpg)

## Features
- IWAD and PWAD support
- Custom WAD launcher
- Per-WAD save folders
- Touch drag joystick
- Physical button controls
- ES8311 audio support
- AXP2101 battery HUD
- Adjustable volume, brightness, battery HUD, and sensitivity

# Demo
![Watch UI](15607.gif)
![Watch UI](15608.gif)
![Watch UI](15609.gif)

## Hardware
https://www.waveshare.com/wiki/ESP32-S3-Touch-AMOLED-2.06

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

## SD Card Layout

```text
SDCARD/
├── doom1.wad
├── doom2.wad
├── plutonia.wad
├── tnt.wad
└── doomsaves/
    ├── doom1/
    ├── doom2/
    ├── plutonia/
    └── tnt/

## Performance Notes
- RGB565 rendering pipeline
- Precomputed scaling maps
- Shared display initialization
- Minimal in-game overlays
- Optimized touch and control polling

