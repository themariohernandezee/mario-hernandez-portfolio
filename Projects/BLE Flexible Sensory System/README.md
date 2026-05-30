# Flexible BLE Pressure Sensing System

## Project Overview

Designed and developed a custom modular PCB platform for wireless pressure sensing and real-time Bluetooth Low Energy (BLE) data transmission. The system was created to support dysphagia research by measuring pressure distribution from multiple force-sensitive sensors and transmitting the collected data wirelessly for analysis.

## Design Objectives

- Acquire data from multiple force-sensitive resistor (FSR) sensors
- Provide stable and repeatable sensor measurements
- Transmit sensor data wirelessly using BLE to an external device
- Create a compact modular architecture for development and testing
- Minimize sensor noise through analog signal conditioning

## System Architecture

The system consists of two interconnected hardware modules:

### Programming & Debug Interface Board
- STM32F103 microcontroller
- USB communication interface
- SWD programming capability
- UART bridge functionality
- Power distribution to sensor board

### Flexible BLE Sensor Board
- nRF52840 BLE SoC
- Multi-channel sensor acquisition
- Analog signal conditioning circuitry
- Battery and programming power support
- Wireless BLE communication

## Key Technologies

- nRF52840 Bluetooth Low Energy SoC
- STM32F103 Microcontroller
- 2-Layer Flexible PCB Design
- Force Sensitive Resistors (FSRs)
- Analog Signal Conditioning
- Bluetooth Low Energy (BLE)
- Altium Designer
- Embedded C Programming

## Engineering Challenges

### Sensor Noise Reduction

Initial testing revealed significant noise due to the high-impedance characteristics of the force-sensitive resistor network.

Several signal conditioning configurations were evaluated:

- 1 MΩ resistor divider (no filtering)
- 1 MΩ resistor divider with RC filtering
- 500 kΩ resistor divider with RC filtering

Experimental testing demonstrated improved signal stability using the optimized resistor network and RC filtering approach.

### Modular Architecture

The design was partitioned into separate programming/debug and sensor acquisition boards to simplify development, testing, and future hardware revisions. Additionally, the compact footprint of the board allows it to be placed in the mouth to accurately measure the force distribution.

## Engineering Skills Demonstrated

- PCB Design and Layout
- Component Selection
- Mixed Signal Embedded Systems Development
- BLE Communications
- Analog Circuit Design
- Hardware Debugging
- Sensor Integration
- Experimental Validation
- System-Level Architecture Design

## Project Files

- System Block Diagram
- Manufactured PCB Photos
- Hardware Prototype Images
- Sensor Stability Validation Results
- Full Technical Report

## Outcome

Successfully designed, assembled, and validated a custom wireless pressure sensing platform capable of acquiring multi-channel force data and transmitting measurements over Bluetooth Low Energy for research applications.
