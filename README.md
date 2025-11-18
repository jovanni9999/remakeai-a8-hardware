# Remake.ai A8 Hardware (Sunber A8 Mainboard Replacement)

This repository contains the hardware design for the Remake.ai-enabled
Sunber A8 robot vacuum cleaner.

## Scope

- New main PCB based on **STM32H7 + ESP32-S3**
- Pin-compatible with Sunber A8 motors, sensors and LiDAR
- Power distribution from 14.4 V battery rail
- Connectors for:
  - Wheel motors + encoders
  - Main brush motor
  - Side brush motor
  - Vacuum fan motor
  - Water pump motor
  - LiDAR UART
  - IR cliff sensors
  - IR wall/side sensors
  - Docking IR sensors
  - Bumper sensors
  - “Picked up” / lift sensor
  - Buttons
  - Speaker / buzzer
  - USB-C (debug + power)

## Structure

- `kicad/a8-mainboard/` – KiCad project files  
- `mechanical/` – Mechanical notes and chassis dimensions  
- `docs/` – Hardware reverse-engineering notes  
