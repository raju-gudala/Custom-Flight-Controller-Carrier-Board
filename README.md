# Custom Flight Controller Carrier Board

A custom carrier board designed to support the **Pixhawk Cube Orange+** flight controller. The primary objective of this design is to provide a more **ergonomic, organized, and user-friendly interface for port connections**, making it easier to integrate the flight controller with external sensors, peripherals, communication interfaces, and other UAV systems.

The complete hardware design, including schematic capture and PCB layout, was developed using **KiCad**.

## Features

* Custom carrier board designed for **Pixhawk Cube Orange+**
* Ergonomically arranged connectors for easier system integration
* Organized port connections for improved accessibility and wiring
* Custom PCB layout optimized around the Cube Orange+ form factor
* Custom footprints and symbols included for project-specific components
* Complete schematic and PCB design developed in KiCad
* Designed for UAV and flight-control system integration
* Includes PCB visualization images for reference

## Design Overview

The carrier board acts as an interface between the **Pixhawk Cube Orange+** flight controller and external UAV peripherals.

Instead of connecting multiple peripherals directly to the flight controller in a tightly packed arrangement, the carrier board brings the required interfaces to more accessible locations on the PCB. This provides a cleaner wiring arrangement and makes the overall flight-control system easier to assemble, inspect, and maintain.

### Key Design Objectives

* **Ergonomics** — Position commonly used connectors where they are easily accessible.
* **Ease of Integration** — Simplify connections between the Cube Orange+ and external peripherals.
* **Serviceability** — Make wiring, troubleshooting, and maintenance easier.
* **Compact Integration** — Provide a dedicated carrier PCB around the Cube Orange+.
* **Customizability** — Allow the carrier board to be adapted for specific UAV applications.

## Hardware

The board is designed around the **Pixhawk Cube Orange+** flight controller and provides the required physical interface between the flight controller and connected UAV peripherals.

The design includes:

* Cube Orange+ carrier interface
* External peripheral connectors
* Custom connector footprints
* Custom symbols and footprints
* PCB mounting and mechanical interface
* Organized signal and power routing

## Repository Contents

```text
├── Custom Footprints/              # Custom KiCad footprints, symbols and 3D models
├── carrier_board_foot.pretty/      # Project-specific PCB footprints
├── carrier_board_symbols.kicad_sym # Custom schematic symbols
├── fp-lib-table                    # KiCad footprint library configuration
├── Ti-Circle v1.0.kicad_pro        # KiCad project file
├── Ti-Circle v1.0.kicad_sch        # Schematic
├── Ti-Circle v1.0.kicad_pcb        # PCB layout
├── Ti-Circle v1.0_top.png          # Top-side PCB view
├── Ti-Circle v1.0_bottom.png       # Bottom-side PCB view
└── README.md
```

## PCB Layout

The PCB layout was developed with emphasis on:

* Ergonomic connector placement
* Accessible peripheral interfaces
* Clean signal routing
* Practical component placement
* Mechanical compatibility with the Cube Orange+
* Maintainable wiring and system integration

The top and bottom PCB renders are included in the repository for quick visual reference.

## Design Workflow

The complete design was developed using **KiCad**, covering the complete PCB design workflow:

```text
Design Requirements
       ↓
Schematic Design
       ↓
Component & Library Selection
       ↓
PCB Placement
       ↓
PCB Routing
       ↓
Design Verification
       ↓
3D / Layout Review
       ↓
Manufacturing Files
```

## Tools Used

* **KiCad** — Schematic capture, PCB layout, library management, and design verification

## Project Status

**Status:** Custom carrier board design completed.

The repository contains the KiCad schematic, PCB layout, custom libraries, footprints, and reference PCB images required to continue development or review the design.

## License

This project is currently provided for reference and development purposes. If you intend to reuse, modify, or distribute the design, please specify an appropriate open-source hardware license.
