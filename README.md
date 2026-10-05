# LaraOS

A modern smartwatch firmware for the ESP32-S3 using ChronosESP32.

## My Contribution

I designed and developed the LaraOS smartwatch firmware and embedded UI architecture. My work includes:

- Developed the ESP32-S3 firmware using PlatformIO.
- Integrated ChronosESP32 for Bluetooth communication with the Android phone.
- Built the OLED display and screen-management system for the SSD1306 128×64 display.
- Implemented real-time phone-to-watch information handling.
- Developed interfaces for navigation, notifications, incoming calls, battery status, music controls, and weather.
- Designed the UI and state-management flow for different watch screens.
- Tested and debugged Bluetooth connectivity and real-time data updates between the phone and ESP32-S3.


## Hardware

- ESP32-S3-WROOM-1-N16R8
- SSD1306 128×64 OLED (I2C)
- Android Phone running Chronos


## Status

🚧 Under Development


## Current Features

- Google Maps Navigation
- Real-time Notifications
- Incoming Call Information
- Phone Battery Status
- Watch Battery Status
- Bluetooth Connection Status
- Music Controls
- Weather Information
- SSD1306 OLED-based Watch Interface
- ESP32-S3 and ChronosESP32 Integration

## In Development

- Custom Android Companion App
- AI Assistant
- Expanded Watch Interactions
- Additional Navigation and Telemetry Features
- UI/UX Improvements


## Architecture

Android Phone
      ↓
Bluetooth / ChronosESP32
      ↓
ESP32-S3
      ↓
SSD1306 OLED

The watch receives real-time phone information and renders
navigation, notifications, calls, battery and other telemetry
on the OLED display.


## License

MIT

