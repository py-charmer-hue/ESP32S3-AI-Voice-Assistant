# ESP32-S3 AI Voice Assistant – Firmware

A pre-built firmware package for an **ESP32-S3 AI Voice Assistant**.

This project provides ready-to-flash firmware for compatible ESP32-S3 hardware, allowing users to build and operate an AI-powered voice assistant without compiling or writing firmware code.

## 🚀 Project Overview

The device is a compact, portable AI voice assistant built around the **ESP32-S3**, featuring:

- 🎙️ Voice-based AI interaction
- 🖥️ OLED display with animated emoji expressions
- 🌍 Multilingual voice support
- 📄 PDF-based knowledge upload
- 🏠 Smart-home control through Home Assistant
- 🔋 Battery-powered portable operation
- ☁️ Cloud-based AI processing

## 🧠 Firmware Features

- Pre-compiled ESP32-S3 firmware
- No programming or compilation required
- Optimized for **ESP32-S3 N16R8**
  - 16 MB Flash
  - 8 MB PSRAM
- Digital I2S microphone input
- I2S DAC amplifier audio output
- OLED display support
- Physical button controls
- Cloud-based voice and AI processing

## 📦 Firmware Files

The `Firmware Files` directory contains the pre-compiled binaries required to flash the device.

| File | Flash Address |
|---|---:|
| `bootloader.bin` | `0x0` |
| `partition-table.bin` | `0x8000` |
| `ota_data_initial.bin` | `0xD000` |
| `xiaozhi.bin` | `0x20000` |
| `generated_assets.bin` | `0x800000` |

### ⚠️ Important

**Use the exact flash addresses listed above.**

Incorrect addresses may prevent the ESP32-S3 from booting correctly or cause the device to malfunction.

Before flashing the firmware, it is recommended to watch the complete project video to understand the hardware setup, flashing procedure, and overall workflow.

## 🔧 Hardware

The firmware is intended for compatible **ESP32-S3 N16R8** hardware with peripherals such as:

- ESP32-S3
- I2S digital microphone
- I2S DAC amplifier
- OLED display
- Physical control buttons
- Battery/power system

Hardware compatibility may vary depending on the board and peripheral configuration.

## 📁 Repository Structure

```text
ESP32S3-AI-Voice-Assistant/
│
├── Firmware Files/
│   ├── bootloader.bin
│   ├── partition-table.bin
│   ├── ota_data_initial.bin
│   ├── xiaozhi.bin
│   └── generated_assets.bin
│
├── Schematic/
│   └── ...
│
└── README.md
