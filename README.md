# STM32 Password-Protected Lock System

<p align="center">
  <img src="Fusion%20Assembled%20View.png" width="750">
</p>

A complete embedded systems project featuring custom STM32 firmware, PCB design, hardware prototyping, and a custom 3D-printed enclosure.

## Overview

Designed and built a complete embedded password-protected lock system using an STM32 microcontroller. The project integrates embedded firmware, hardware prototyping, PCB design, and mechanical enclosure design into a fully functional device. The system was first validated on a breadboard before being transitioned to a custom PCB designed in Altium Designer and housed inside a custom enclosure designed in Fusion 360.

## Features

- 4-button password authentication system
- Password change mode with current password verification
- Three-attempt security lockout with cooldown timer
- LED indicators for system feedback
- Buzzer feedback for access status
- UART debugging through PuTTY
- Custom PCB designed in Altium Designer
- Custom enclosure designed in Fusion 360

## Hardware

- STM32F401RE (NUCLEO-F401RE)
- Push Buttons
- LEDs
- Active Buzzer
- 2 220 Ohm Resistors
- 1 1k Ohm Resistor
- NPN Transistor
- UART Communication

## Software & Tools

- STM32CubeIDE
- STM32CubeMX
- Altium Designer
- Autodesk Fusion 360
- PuTTY

## Project Gallery

| Breadboard Prototype | Altium Schematic |
|---|---|
| <img src="Breadboard%20Prototype.jpg" width="350"> | <img src="Altium%20Schematic.png" width="350"> |

| PCB Layout | PCB 3D View |
|---|---|
| <img src="Altium%202D%20View.png" width="350"> | <img src="Altium%203D%20View.png" width="350"> |

| Fusion Exploded View | Fusion Final Assembly |
|---|---|
| <img src="Fusion%20Exploded%20View.png" width="350"> | <img src="Fusion%20Assembled%20View.png" width="350"> |
