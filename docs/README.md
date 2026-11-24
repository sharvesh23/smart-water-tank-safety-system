# Smart Water Tank Safety & Monitoring System

An Arduino-based system designed to prevent water overflow in a rooftop tank by automatically switching OFF the water motor when the tank reaches its full level.

## Problem Statement

Our home uses a 2000-litre rooftop water tank filled from a larger main tank using an electric motor. The motor is manually operated through a wall switch and can sometimes be left ON after the tank fills, resulting in water overflow and electricity wastage.

## Proposed Solution

We are developing an Arduino-based safety system that detects the full water level and automatically cuts OFF the motor.

**Manual Start — Automatic Stop**

The system will not automate water filling or automatically start the motor.

## Project Features

- Automatic full-level detection
- Automatic motor cut-off
- Manual motor starting
- Buzzer alert
- LED status indicators
- Future Wi-Fi connectivity
- Mobile notifications
- Tank monitoring dashboard
- Filling history and fault alerts

## Planned Development

| Version | Features |
|---|---|
| V1.0 | Core automatic cut-off |
| V2.0 | Wi-Fi connectivity |
| V3.0 | Mobile push notifications |
| V4.0 | Monitoring dashboard |
| V5.0 | History and analytics |
| V6.0 | Fault detection and reliability |

## Hardware

- Arduino Uno
- Water-level float switch
- Isolated motor-control interface
- LEDs
- Buzzer
- Future ESP32/ESP8266 module

## Safety

The core cut-off must work independently of Wi-Fi and internet connectivity. Household motor switching will use properly rated motor-control equipment, isolation and protective devices.

## Project Status

🟡 Planning & site assessment

## Development Workflow

Build → Test → Document → Commit → Push

## Author

Sharvesh S.
