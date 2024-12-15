# Knitting Machine Yarn Cone Monitoring System

## Overview
This project aims to reduce garment rejections in knitting machines caused by the `Miss-Yarn Error`. The solution involves detecting when the yarn cone's weight falls below a predefined threshold and providing an indicator to replace the yarn cone before it finishes. By implementing this system, downtime is minimized, and production efficiency is improved.

## Features
- **Load Cell Integration:** Measures the weight of the yarn cone in real-time.
- **Threshold Indicator:** Turns on an LED when the weight is below the predefined threshold.
- **Arduino-Powered:** Simple and customizable code for reliable monitoring.
- **Prototyping to Implementation:** Includes schematic design, PCB development, and enclosure design.

## Project Workflow
1. **Setup the Load Cell**
   - Connect and calibrate the load cell with the HX711 amplifier.
2. **Threshold Detection**
   - Deduce the critical weight threshold by testing yarn cones.
3. **Circuit Design**
   - Create a circuit for the load cell, Arduino, and indicator LED.
4. **Prototype Testing**
   - Validate the system's performance with a prototype.
5. **PCB Design and Soldering**
   - Design, fabricate, and assemble a compact PCB.
6. **Enclosure Development**
   - Create a 3D-printed or custom-built enclosure for the device.

## Hardware Requirements
- Load Cell (e.g., 1kg or 5kg)
- HX711 Load Cell Amplifier Module
- Arduino Board (e.g., Arduino Uno or Nano)
- LED and Resistor (for indicator)
- Power Supply (e.g., 5V)
- PCB and Soldering Components (optional for advanced setups)

## Software Requirements
- Arduino IDE
- HX711 Library for Arduino ([Download Here](https://github.com/bogde/HX711))

