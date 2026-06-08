# OmniProbe

**A Universal Open-Source Debugging and Signal Analysis Platform for Embedded Engineers**

OmniProbe is an open-source hardware and firmware platform designed to simplify embedded system development, debugging, and protocol analysis.

Built around the RP2040 microcontroller, OmniProbe combines multiple engineering tools into a single compact device, reducing the need for separate adapters, analyzers, and interface boards.

---

## Why OmniProbe?

Embedded developers often rely on multiple tools for debugging and communication:

* SWD Debug Probe
* USB-to-UART Adapter
* Logic Analyzer
* SPI Debug Tool
* I2C Interface
* GPIO Test Board

OmniProbe aims to bring all of these capabilities into a single open-source platform.

---

## Key Features

### Debugging Interfaces

* SWD Debugging
* JTAG Support
* CMSIS-DAP Compatible Firmware

### Communication Interfaces

* USB to UART Bridge
* SPI Interface
* I2C Interface
* GPIO Access

### Logic Analyzer

* Up to 16 Digital Channels
* RP2040 PIO-Based Sampling Engine
* Planned Sigrok / PulseView Integration

### Multi-Voltage Operation

* 1.8V Support
* 3.3V Support
* 5V Support
* Bidirectional Level Shifting

### Hardware Features

* USB Type-C Connectivity
* ESD Protection
* Polyfuse Protection
* EMI Filtering
* Reverse Polarity Protection

---

## Hardware Architecture

The hardware architecture is divided into several independent modules:

* Power Management
* USB Type-C Interface
* RP2040 Core
* QSPI Flash Memory
* Level Shifting Subsystem
* Debug Interfaces
* Logic Analyzer Engine
* Protection Layer

This modular architecture allows future expansion without redesigning the entire system.

---

## Project Goals

* Open-Source Hardware
* Open-Source Firmware
* Professional Development Tool
* Affordable Manufacturing Cost
* Maker-Friendly Design
* Educational Value
* Extensible Architecture

---

## Repository Structure

```text
OmniProbe/
├── docs/
├── hardware/
├── firmware/
├── software/
├── tests/
└── assets/
```

---

## Current Status


Project Phase: System Architecture & Hardware Design

OmniProbe is currently in the hardware architecture and schematic design phase. The project is being developed as a fully open-source platform, including hardware design files, documentation, and firmware sources.

The first release focuses on establishing a reliable and extensible foundation for debugging, protocol analysis, and embedded development workflows.

Future updates will expand functionality, improve performance, and introduce additional protocol support while maintaining compatibility with the existing hardware platform.
---

## Open Hardware

All design files, schematics, PCB layouts, BOMs, and firmware sources will be publicly available.

The objective of OmniProbe is not only to provide a useful engineering tool, but also to serve as a learning resource for hardware and embedded system developers.

---

## Contributing

Contributions, design reviews, bug reports, feature requests, and pull requests are welcome.

---

## License

MIT License

---

## Disclaimer

OmniProbe is currently under active development. Hardware and firmware specifications may change before the first stable release.
