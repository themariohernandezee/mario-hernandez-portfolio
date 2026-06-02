# Dual DC-DC Converter PCB Design

## Project Overview

Designed and validated a custom dual-function DC-DC converter PCB integrating:

- 12V → 5V Buck Converter
- 5V → 12V Boost Converter

The project demonstrates a complete hardware development workflow including engineering calculations, component selection, LTspice simulation, schematic capture, PCB layout, BOM generation, and design verification using Altium Designer.

## Key Skills Demonstrated

- Power Electronics Design
- Schematic Capture
- Component Selection
- PCB Layout
- LTspice Simulation
- BOM Generation
- Design Verification
- Board Bring-Up Planning
- ERC/DRC Validation

## Tools Used

- Altium Designer
- LTspice
- TPS54331D Buck Regulator
- TPS61040 Boost Converter

## Design Highlights

### Buck Converter
- 12V → 5V conversion
- TPS54331D switching regulator
- 15 µH power inductor
- 47 µF output capacitor
- Feedback network designed for regulated 5 V output

### Boost Converter
- 5V → 12V conversion
- TPS61040 boost controller
- 10 µH power inductor
- 47 µF output capacitor
- Feedback network designed for regulated 12 V output

## Engineering Activities

- Performed duty-cycle calculations and component sizing
- Selected manufacturer components and generated BOMs
- Created production-style schematics in Altium Designer
- Developed a two-layer PCB layout with ground-plane implementation
- Performed ERC and DRC verification
- Validated startup response, switching-node behavior, and output regulation using LTspice

## Documentation

See project report and supporting design files included in this repository.

## Future Work

- PCB fabrication
- Hardware bring-up
- Efficiency characterization
- Thermal analysis
- Oscilloscope validation under varying load conditions
