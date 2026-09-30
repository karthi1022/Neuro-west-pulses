# ⚡ Neuro West Pulses - IoT Therapeutic Stimulation Device

An IoT-enabled wearable therapeutic device designed for targeted muscle relief and neuro-stimulation. It provides on-demand dual-mode therapy (vibration massage and localized heat therapy) controlled wirelessly via the Blynk IoT mobile application.

## Hardware & Components
- Microcontroller: ESP32 
- Actuators:
  - Miniature Vibration Motor (for mechanical pulse stimulation)
  - Flexible Heating Pad (for thermal therapy)
- Driver Circuit:  Relay Modules for high-current actuation
- Power Supply: Regulated 5V DC power unit

## Tech Stack & Communication
- Firmware: Embedded C 
- IoT Platform: Blynk IoT Cloud
- Wireless Protocol: Wi-Fi (Direct Blynk Server Telemetry)
- Mobile Control: Custom Blynk App Dashboard with tactile toggle switches

## Key Features
- Independent Dual-Mode Control: Dedicated Blynk mobile switches to trigger vibration stimulation and thermal heating separately or simultaneously.
- Real-Time IoT Responsiveness: Instant hardware triggering over Wi-Fi with negligible latency.
- Safety Interlocks: Safe current regulation through dedicated driver stages to protect the heating element and motor coils.
- Remote Telemetry: Visual status feedback on the mobile dashboard indicating active stimulation modes.
