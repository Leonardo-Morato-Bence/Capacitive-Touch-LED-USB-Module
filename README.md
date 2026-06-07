# Capacitive-Touch-LED-USB-Module
Compact USB-powered touch-activated lighting module. Includes TTP223 capacitive touch sensor, an NPN transistor and five white LEDs.

<img width="1248" height="464" alt="image" src="https://github.com/user-attachments/assets/00e1604d-fd3f-4014-abeb-50445b3a1936" />

---

## Overview

The Capacitive Touch LED USB Module is a compact demonstration platform designed to showcase capacitive touch sensing technology in a simple and intuitive way.

The module uses the TTP223 capacitive touch sensor to replace conventional mechanical switches, providing reliable touch activation through a PCB touch pad. When touched, the sensor output drives a transistor stage that powers five white LEDs.

Powered directly from a USB Type-A connector, the module requires no firmware or programming.

---

## Features

- USB powered (5V)
- TTP223 capacitive touch sensor
- Touch-sensitive PCB pad
- Five white LEDs
- Individual current-limiting resistors
- MMBT3904 transistor
- Plug-and-play operation
- No firmware required
- Compact USB-stick form factor
- Adjustable touch sensitivity

---

## Applications

- Touch technology demonstrations
- Educational electronics projects
- USB decorative lighting
- Human-machine interface studies
- DIY electronics projects
- Sensor evaluation platform
- Capacitive sensing experiments

---

## Technical Specifications

| Parameter | Value |
|------------|------------|
| Supply Voltage | 5V USB |
| Operating Current | 90 mA Typical |
| Maximum Operating Current | 120 mA |
| Touch Detection Distance | 0.5 mm – 2.0 mm |
| Number of LEDs | 5 |
| LED Current (each) | 10 mA – 17 mA |
| Touch Sensor | TTP223-BA6 |
| LED Driver | MMBT3904 |
| PCB Dimensions | 55 mm × 18 mm |

---

## System Architecture

<img width="660" height="294" alt="image" src="https://github.com/user-attachments/assets/f4f63804-8f39-4d10-93b6-cce3f507eea1" />

---

## Design Highlights

### Capacitive Touch Interface

The TTP223 touch sensor enables:

- Contactless activation
- High reliability
- Elimination of mechanical wear
- Simple user interaction

The touch pad is integrated directly into the PCB.

### LED Driver Stage

The LED array is driven through an MMBT3904 transistor.

Benefits include:

- Stable switching operation
- Reduced sensor loading
- Improved current handling capability

### Adjustable Sensitivity

Touch sensitivity may be modified by changing the external capacitor connected to the TTP223 sensor.

This allows optimization for:

- Different PCB materials
- Protective overlays
- Environmental conditions

---

## Main Components

| Component | Function |
|------------|------------|
| TTP223-BA6 | Capacitive touch sensor |
| MMBT3904 | NPN transistor driver |
| White LEDs | Light source |
| 150 Ω Resistors | LED current limiting |
| USB Type-A Connector | Power input |

---

## USB Pinout

| Pin | Name | Description |
|------|------|------|
| 1 | VBUS | +5V USB Supply |
| 2 | D- | Not Connected |
| 3 | D+ | Not Connected |
| 4 | GND | Ground |

---

## Hardware Images

### 3D

<img width="1177" height="330" alt="image" src="https://github.com/user-attachments/assets/64d90ca0-2302-482b-a1ec-57f6d68e1715" />

### PCB Top Side

<img width="959" height="270" alt="image" src="https://github.com/user-attachments/assets/fc73e787-99ea-4207-ad73-bd5f73690463" />

### PCB Bottom Side

<img width="955" height="259" alt="image" src="https://github.com/user-attachments/assets/f112f14a-7591-4374-b4b9-be400b1a606c" />

---

## Electrical Characteristics

| Parameter | Min | Typ | Max |
|------------|------------|------------|------------|
| Supply Voltage | 4.5V | 5.0V | 5.5V |
| Operating Current | — | 90 mA | 120 mA |
| Touch Detection Distance | — | 0.5 mm | 2.0 mm |
| LED Current (per LED) | — | 10 mA | 17 mA |

---
