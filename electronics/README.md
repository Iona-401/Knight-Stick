# Electronics

This directory contains the complete electronics design for the **Knight Stick**
flight stick, including the schematic, PCB layout, and manufacturing outputs.

The electronics are built around an **ESP32**, providing USB and/or wireless
capabilities suitable for use as a flight simulation controller or general
HID device.

## Contents

- `kicad/`  
  Source design files created with **KiCad**, including:
  - Schematics
  - PCB layout
  - Project configuration files  
  These files represent the authoritative source for the electronics design.

- `gerbers/`  
  Fabrication-ready Gerber and drill files, organized by hardware revision.
  These files can be used directly with PCB manufacturers.

- `bom/`  
  Bill of Materials (BOM) files listing all electronic components required to
  assemble the PCB.

## Manufacturing Notes

- Gerber files are provided for convenience; always refer to the KiCad source
  files if modifications are required.
- Check the BOM and schematic carefully before ordering or assembling boards.

## License

All electronics design files in this directory are licensed under the  
**CERN Open Hardware License v2 – Strongly Reciprocal (CERN-OHL-S)**.

See the root `LICENSE-hardware.txt` file for full license terms.
