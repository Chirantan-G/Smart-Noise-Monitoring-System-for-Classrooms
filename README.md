# Smart-Noise-Monitoring-System-for-Classrooms
A simple Arduino-based noise monitoring system developed during a hardware hackathon.

## Features
- Detects ambient sound levels
- OLED display output
- Noise threshold alerts
- LED indicators for quiet/noisy environments
- Violation counter

## Components Used
- Arduino Uno
- Sound Sensor Module
- OLED Display (SSD1306)
- Red and Green LEDs
- Jumper wires

## How It Works
The sound sensor continuously monitors environmental noise levels.  
If the sound exceeds a predefined threshold:
- Red LED turns ON
- Green LED turns OFF
- OLED displays "NOISY!"
- Violation counter increases

Otherwise:
- Green LED remains ON
- OLED displays "QUIET"

## Libraries Used
- Adafruit_GFX
- Adafruit_SSD1306
- Wire

## Team Project
Built during a college hardware hackathon.
