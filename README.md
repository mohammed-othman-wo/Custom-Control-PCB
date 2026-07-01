# 🔌 Custom Control PCB — Mimar Najd Co.

Safety monitoring system for disability residence bathrooms — PIR-triggered voice communication via custom PCB with 3D-printed enclosure.

![KiCAD](https://img.shields.io/badge/PCB-KiCAD-blue) ![Hardware](https://img.shields.io/badge/Type-Custom%20PCB-green) ![Client](https://img.shields.io/badge/Client-Mimar%20Najd%20Co.-orange)

---

## Overview

A custom-designed PCB control circuit built for Mimar Najd Co. The system monitors bathroom occupancy in disability residences using a PIR sensor. When motion is detected, it activates a microphone and speaker via relay control, enabling two-way voice communication for emergency response.

Full project ownership: schematic design, PCB layout, BOM selection, component sourcing, and custom enclosure design and 3D printing.

---

## Features

- ✅ PIR motion/occupancy detection
- ✅ Relay-controlled microphone and speaker activation
- ✅ Complete on-board control logic (no external MCU required)
- ✅ Custom 3D-printed enclosure for field deployment
- ✅ Designed for reliability and real-world installation

---

## Hardware Design

| Element | Details |
|---|---|
| PCB Tool | KiCAD / EasyEDA |
| Power Input | 12V DC |
| Sensor | PIR (passive infrared) |
| Output | Relay × 2 (microphone + speaker) |
| Enclosure | Custom 3D-printed |

---

## Project Scope

| Phase | Deliverable |
|---|---|
| Schematic | Full circuit design in KiCAD |
| PCB Layout | Routed board with DRC clearance |
| BOM | Component selection and sourcing |
| Fabrication | Gerber files sent to manufacturer |
| Enclosure | SolidWorks design → 3D printed |
| Deployment | Installed at client site |

---

## System Logic

```
PIR Sensor detects motion
        ↓
Relay 1 closes → Microphone activated
Relay 2 closes → Speaker activated
        ↓
Two-way voice communication enabled
        ↓
Staff notified of potential emergency
```

---

## Files

```
/schematic    → KiCAD schematic files
/pcb          → PCB layout + Gerber files
/bom          → Bill of materials
/enclosure    → SolidWorks + STL files
```
