# 💡 STM32 Sound-Reactive LED Strip (NeoPixel)

## Overview
This is a microcontroller project utilizing the **STM32F411E DISCO** board to drive a **WS2812B LED strip** (NeoPixel) with dynamic light shows. The core feature is the ability to create effects that react to ambient sound via the **MAX9814** microphone module.

## Core Technology
The system employs **PWM** (at 800kHz) and **DMA** to efficiently transfer the RGB data buffer, ensuring high-speed LED control. The sound signal is processed using **ADC** (Analog-to-Digital Conversion).

## Key Features (7 Modes)
* **Default Modes:** Standard animations like `RAINBOW`, `STROBE`, and `COLOR_TRANSITION`.
* **Sound-Reactive Modes:**
    * `ADC_GLOW`: LED brightness scales with sound intensity.
    * `ADC_VOLUME_BAR`: Number of illuminated LEDs scales with sound intensity.

## Hardware Used
* STM32F411E DISCO
* WS2812B LED Strip (29 LEDs)
* MAX 9814 Sound Module

## 🔗 Demo Videos & Source Code
| Description | Link (Google Drive) |
| :--- | :--- |
| **Video Demo (ADC VOLUME BAR)** | [Updating] |
