# Hardware: Bill of Materials (BOM)

## 1. Objective
Define the necessary components for the DRM downconverter circuit, ensuring compatibility with the target IF bandwidth.

## 2. Component Breakdown
- **Mixer:** High-linearity mixer for frequency downconversion.
- **Local Oscillator (LO):** Stable oscillator circuit tuned for target IF offset.
- **Filter (BPF/LPF):** Passive/Active components to isolate the 12 kHz IF.
- **Passives:** Resistors (precision), capacitors (low-ESR), and inductors for matching networks.

## 3. Implementation Notes
- Use metal-film resistors to minimize thermal noise.
- Ensure proper grounding for shielding the oscillator stage.
