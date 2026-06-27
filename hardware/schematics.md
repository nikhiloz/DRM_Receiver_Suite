# Hardware: Schematics

## 1. Objective
Provide a visual representation of the RF downconverter signal path.

## 2. Diagram
![Schematic Flow](../../glossary/diagrams/schematic_flow.png)

## 3. Component Breakdown
- **RF Input:** Signal from analog receiver IF.
- **Mixer/LO Stage:** The core downconversion block.
- **Output Stage:** Buffer to match PC sound card input impedance.

## 4. Implementation Notes
- Keep trace lengths short for RF signal paths.
- Add decoupling capacitors near the mixer IC power pins.
