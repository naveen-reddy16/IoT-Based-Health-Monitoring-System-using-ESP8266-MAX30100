# IoT-Based Health Monitoring System using ESP8266 & MAX30100

## Overview

This project is an IoT-based real-time health monitoring system developed using the ESP8266 NodeMCU and MAX30100 Pulse Oximeter Sensor. The system continuously measures the user's Heart Rate (BPM) and Blood Oxygen Saturation (SpO₂), then uploads the readings to a cloud platform for remote monitoring.

The project is designed for telemedicine, home healthcare, elderly patient monitoring, and wearable health applications.

---

## Features

- Real-time Heart Rate Monitoring
- Real-time SpO₂ Monitoring
- Wireless Wi-Fi Communication
- Cloud Data Upload
- Serial Monitor Output
- Low-cost IoT Healthcare Solution

---

## Components Used

| Component | Quantity |
|------------|----------|
| ESP8266 NodeMCU | 1 |
| MAX30100 Pulse Oximeter | 1 |
| USB Cable | 1 |
| Breadboard | 1 |
| Jumper Wires | Several |

---

## Software Used

- Arduino IDE
- ESP8266 Board Package
- MAX30100 Library
- PulseOximeter Library
- ThingSpeak / Blynk Cloud

---

## Pin Connections

| MAX30100 | NodeMCU |
|-----------|----------|
| VIN | 3.3V |
| GND | GND |
| SDA | D2 (GPIO4) |
| SCL | D1 (GPIO5) |

---

## Working Principle

1. MAX30100 measures Heart Rate and SpO₂.
2. ESP8266 reads sensor values.
3. ESP8266 connects to Wi-Fi.
4. Data is displayed on Serial Monitor.
5. Sensor readings are uploaded to the cloud.
6. Doctors or users can monitor data remotely.

---

## Libraries Required

Install the following libraries from Arduino Library Manager:

- ESP8266WiFi
- Wire
- MAX30100_PulseOximeter
- ESP8266HTTPClient

---

## Applications

- Remote Patient Monitoring
- Telemedicine
- Elderly Care
- Smart Hospitals
- Home Healthcare
- IoT Medical Devices

---

## Future Enhancements

- Body Temperature Monitoring
- ECG Integration
- OLED Display
- SMS Alerts
- Firebase Database
- Mobile App Dashboard

---

## Output

Example:

Heart Rate: 74 BPM

SpO₂: 98%

Uploading to Cloud...

Upload Successful

---

## Author

Bandi Naveen Reddy

B.Tech Electronics and Communication Engineering

KL University
