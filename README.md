## Overview
The Surveillance Camera Car using ESP32-CAM is a Wi‑Fi‑controlled robotic vehicle capable of streaming live video and receiving movement commands through a mobile web browser. The system enables remote monitoring of inaccessible or hazardous environments and supports real‑time navigation using an embedded web interface.

This project demonstrates the integration of embedded systems, wireless communication, motor control, and IoT‑based surveillance.

## Features
- Live video streaming over Wi‑Fi
- Remote vehicle control via web browser
- Movement directions: Forward / Backward / Left / Right / Stop
- Motor speed control
- Light intensity control
- Mobile‑friendly control interface

## Applications
- Remote surveillance in restricted or hazardous environments
- Disaster zone monitoring
- Industrial inspection
- Security patrol robots

## Hardware Components
- ESP32‑CAM module (OV2640 camera)
- USB‑to‑serial adapter (or Arduino UNO for passthrough)
- L298N motor driver
- DC motors with chassis
- 7–12 V battery
- Breadboard and jumper wires

## System Architecture
- ESP32‑CAM acts as the Wi‑Fi server, camera stream source, and motor controller interface.
- L298N motor driver controls motor direction and speed (via PWM).
- A mobile browser connects to the ESP32‑CAM to view video and send control commands.

## Working Principle
