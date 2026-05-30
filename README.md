<div align="center">

# 🗄️ Board-Assets

### Open PCB Design Resource Library for Embedded & Hardware Engineers

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/amirslz74/Board-Assets?style=flat-square&color=orange)](https://github.com/amirslz74/Board-Assets/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/amirslz74/Board-Assets?style=flat-square)](https://github.com/amirslz74/Board-Assets/commits)

> A centralized, community-friendly library of PCB design assets — datasheets, schematic symbols, footprints, logos, layout guidelines, and engineering references. Free to use. Open to contributions.

</div>

---

## 📦 What's Inside

```
Board-Assets/
│
├── 📂 Data Sheets/
│   ├── MCU/               # STM32, ESP32, ATmega, RP2040, ...
│   ├── Power/             # LDO, Buck, Boost, Gate Drivers, ...
│   ├── Sensors/           # IMU, Temperature, Pressure, ...
│   ├── Communication/     # CAN transceivers, RS-422, USB, ...
│   └── Passives/          # Capacitors, Inductors, Resistors, ...
│
├── 📂 PCB-Assets/
│   ├── Logos/             # Manufacturer logos for silkscreen
│   ├── Symbols/           # Schematic symbols (KiCad / Altium)
│   ├── Footprints/        # PCB footprints (KiCad / Altium)
│   └── 3D-Models/         # STEP files for components
│
├── 📂 Design-References/
│   ├── Layout-Guidelines/ # EMI/EMC, power planes, grounding
│   ├── App-Notes/         # Application notes from manufacturers
│   └── Checklists/        # Bring-up, review, and QA checklists
│
├── 📂 Librarys/
│   ├── EasyEDA-pro/      
│   ├── EasyEDA/          
│   ├── Altiume/  
│   └── KiCad/         
│
└── 📂 Simulation/
```

---

## 🛠️ Supported Tools

| Tool | Usage |
|------|-------|
| ![Altium](https://img.shields.io/badge/Altium_Designer-A5915F?style=flat-square) | Symbols, Footprints, 3D Models |
| ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square) | Symbols, Footprints |
| ![EasyEDA](https://img.shields.io/badge/EasyEDA-1DB954?style=flat-square) | Schematic & PCB references |
| ![Proteus](https://img.shields.io/badge/Proteus-Simulation-blue?style=flat-square) | SPICE models |
| ![LTspice](https://img.shields.io/badge/LTspice-Simulation-red?style=flat-square) | SPICE models |
| ![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-blue?style=flat-square) | MCU references |
| ![ESPIDF](https://img.shields.io/badge/STM32CubeIDE-red?style=flat-square) | MCU references |
---

## 📋 Datasheets Coverage

| Category | Examples |
|----------|---------|
| **MCU** | STM32F1/F4, ESP32, ATmega328, RP2040 |
| **Power** | AMS1117, MP2307, IR2104, IRFZ44N |
| **Communication** | SN65HVD230 (CAN), MAX485 (RS-422), CH340 (USB) |
| **Sensors** | MPU-6050, DS18B20, BME280, HX711 |
| **Display** | SSD1306, ILI9341, ST7789 |

---

## 🎨 PCB Logos & Silkscreen Assets

Ready-to-use logos for PCB silkscreen layer:

- ⚡ Warning / High Voltage symbols
- 🔌 Connector polarity markers
- 🏭 Manufacturer logos (CE, RoHS, WEEE)
- 🔧 Custom board identity marks

All in **SVG**, **DXF**, and **footprint-ready** formats.

---

## 🤝 Contributing

This is a **community resource** — contributions are highly encouraged!

### How to Contribute

```bash
# 1. Fork the repository
git fork https://github.com/amirslz74/Board-Assets

# 2. Add your files in the correct folder
# 3. Update the relevant README section
# 4. Open a Pull Request with a short description
```

### What We Accept

- ✅ Datasheets (PDF) for any electronic component
- ✅ Schematic symbols (KiCad `.kicad_sym` / Altium `.SchLib`)
- ✅ PCB footprints (KiCad `.kicad_mod` / Altium `.PcbLib`)
- ✅ STEP / 3D models for components
- ✅ Logos and silkscreen assets (SVG / DXF)
- ✅ Layout guidelines and application notes
- ✅ LTspice simulation files

### Naming Convention

```
DataSheets/MCU/STM32F103C8T6_datasheet.pdf
PCB-Assets/Footprints/KiCad/SOT-23-5.kicad_mod
PCB-Assets/Logos/CE-mark.svg
```

---

## 📐 Design Guidelines Included

- ✅ EMI/EMC layout best practices
- ✅ Power plane and ground pour strategies
- ✅ Differential pair routing rules (CAN, USB, RS-422)
- ✅ Decoupling capacitor placement
- ✅ High-current trace width calculator references
- ✅ Board bring-up checklist

---

## 📜 License

MIT License — All assets are free to use in personal and commercial projects.
Please verify component datasheets are publicly available before contributing.

---

<div align="center">

**Maintained by [Amir Salehzadeh](https://github.com/amirslz74)**

*5+ years · 40+ PCBs shipped · Built from real production experience*

⭐ Star this repo to support the project · 🍴 Fork it · 🤝 Contribute

</div>