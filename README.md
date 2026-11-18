# AlphaPad

### A compact, custom-built 9-key macropad with an OLED display.

![Project Status](https://img.shields.io/badge/Project-Open%20Source-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Hardware](https://img.shields.io/badge/Hardware-Custom%20PCB-orange)

---

## About

**AlphaPad** is a custom-designed 9-key macropad built to make everyday computer interactions faster and more convenient.

Designed with a dedicated PCB, custom CAD enclosure and firmware, AlphaPad brings together hardware and software in a compact desktop peripheral.

The project focuses on creating a functional, customizable and self-designed input device.

## Features

- **9 Physical Keys** – Dedicated buttons for customizable actions.
- **OLED Display** – A compact display for visual feedback.
- **Custom PCB** – A dedicated circuit board designed for the project.
- **Custom Enclosure** – CAD-designed housing for the hardware.
- **Custom Firmware** – Software responsible for handling inputs and device functionality.
- **Open Source** – Hardware and firmware files available for exploration and modification.

## Repository Structure

```text
AlphaPad/
│
├── CAD/
│   └── Enclosure design files
│
├── Firmware/
│   └── Main/
│       └── Main firmware
│
├── PCB/
│   └── PCB and schematic files
│
├── README.md
└── LICENSE
```

## Hardware

The project consists of three main hardware sections:

| Component | Purpose |
|---|---|
| 9 Push Buttons | User input |
| OLED Display | Visual feedback |
| Custom PCB | Hardware interconnection |
| Microcontroller | Firmware execution |
| Custom Enclosure | Physical housing |

*Refer to the PCB and CAD folders for the actual design files.*

## Firmware

The firmware is located in:

`Firmware/Main/`

It handles the macropad's input processing and display functionality.

To explore or modify the firmware:

1. Clone this repository.
2. Open the main firmware project in the appropriate development environment.
3. Review the pin configuration and dependencies.
4. Connect the hardware and upload the firmware.

## CAD Design

The enclosure design files are available in the `CAD/` directory.

These files contain the mechanical design used to develop the physical housing of AlphaPad.

## PCB Design

The `PCB/` directory contains the electronics design files.

You can explore the schematic and PCB layout to understand how the hardware is interconnected.

## Project Goals

AlphaPad was developed to explore:

- Embedded systems development
- Custom PCB design
- Mechanical CAD and enclosure design
- Firmware development
- Hardware-software integration
- Human-computer interaction

## Contributing

AlphaPad is an open-source project.

Suggestions, improvements and contributions are welcome. Feel free to fork the repository and experiment with your own modifications.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Author

**Sudip Bandale**

Designed and developed as a personal hardware engineering project.

---

<p align="center">
  <b>AlphaPad</b><br>
  Built from scratch. Designed to be yours.
</p>
