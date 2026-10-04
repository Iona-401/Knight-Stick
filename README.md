# Knight-Stick 🕹️✈️

An open-source, fully 3D-printable flight stick engineered for high-precision simulation, modular assembly, and custom hardware integration.

---

## Overview

Commercial flight simulation gear is often prohibitively expensive or locked into closed ecosystems. **Knight-Stick** bridges that gap by providing a fully customizable, high-performance flight controller that you can manufacture at home using 3D printing and custom electronics.

Designed with a heavy focus on ergonomic feel, mechanical durability, and low-latency input processing, this project brings together mechanical CAD, PCB design, and embedded firmware.

---

## Key Features

* **Ergonomic & Modular CAD:** Designed for additive manufacturing, optimizing print orientation for strength and tactile comfort.
* **Precision Inputs:** Built around low-latency sensor architecture to ensure smooth, dead-zone-free axis tracking and crisp button actuation.
* **Custom Electronics:** Dedicated PCB layout for clean signal routing and reliable peripheral connections.
* **Open Source:** Complete hardware schematics, firmware source code, and STL/CAD files available for modification and community contribution.

---

## Repository Structure

```text
Knight-Stick/
├── cad/          # 3D printable models, mechanical assemblies, and STEP/STL files
├── hardware/     # Schematics, board layouts, and manufacturing files
├── firmware/     # Microcontroller source code and USB HID implementation
└── docs/         # Build guides, wiring diagrams, and assembly instructions

```

---

## Getting Started & Bill of Materials (BOM)

To build your own Knight-Stick, check out the documentation and release files in the respective directories:

1. **Hardware & Electronics:** Review the `hardware/` folder for schematic diagrams and PCB fabrication files.
2. **Mechanical Parts:** Grab the latest printable parts from the `cad/` folder. Ensure you follow recommended print settings for structural rigidity (e.g., adequate infill and wall counts).
3. **Firmware:** Flash the controller using the source code provided in the `firmware/` directory.

---

## Contributing

Contributions, feedback, and forks are always welcome! If you have ideas for improved gimbal geometry, alternative sensor integrations, or firmware enhancements, feel free to open an issue or submit a pull request.

---

## License

This project is open-source. See the repository for license details.