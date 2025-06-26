# USB-C to USB-A Adapter (Altium Designer)

A simple, compact USB-C (receptacle) to USB-A (plug) adapter designed in **Altium Designer**. This open hardware project provides schematic and PCB layout files for fabricating a basic USB 2.0 interface adapter — useful for prototyping, embedded systems, or custom cables.

##  Features

- USB-C (plug) to USB-A (male receptacle)
- USB 2.0 (data lines only — D+/D−, VBUS, GND)

##  Getting Started

To open and modify this project:

1. Install **Altium Designer** 
2. Clone or download this repository.
3. Open the `USBC2USB.PrjPcb` file in Altium.
4. Review the schematic and PCB layout.
5. Generate outputs (Gerbers, BOM, etc.) if needed.

##  Notes

- This design supports **USB 2.0** (not USB 3.0/3.1).
- Only basic wiring is implemented (VBUS, GND, D+, D−). CC logic is handled passively for standard downstream devices.
- Ensure proper ESD and overcurrent protection when integrating into larger systems.

##  Preview


## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

