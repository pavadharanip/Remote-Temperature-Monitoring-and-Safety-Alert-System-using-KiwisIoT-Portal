# 🌡️ IoT-Based Smart Temperature Monitoring and Alert System

## 📌 Project Overview

This project is designed to monitor surrounding temperature using a DHT11 temperature sensor and NodeMCU ESP8266. The measured temperature is displayed on the KiwisIoT dashboard for remote monitoring.

When the temperature reaches or exceeds the predefined threshold of **33°C**, the system automatically activates an LED and buzzer to provide an alert. When the temperature falls below the threshold, both the LED and buzzer turn OFF.

## 🎯 Objectives

- Monitor temperature using the DHT11 sensor.
- Display temperature readings remotely through KiwisIoT.
- Detect temperature levels above a predefined threshold.
- Generate automatic alerts using an LED and buzzer.
- Understand IoT-based environmental monitoring.

## 🛠️ Components Required

- NodeMCU ESP8266
- DHT11 Temperature Sensor
- LED
- Active Buzzer
- 220Ω Resistor
- Breadboard
- Jumper Wires
- USB Cable

## 💻 Software Required

- Arduino IDE
- ESP8266 Board Package
- KiwisIoT Platform
- DHT Sensor Library by Adafruit
- Adafruit Unified Sensor Library
- KiwisIoT Library

## 🔌 Pin Connections

| Component | NodeMCU Pin |
|---|---|
| DHT11 DATA | D2 |
| DHT11 VCC | 3.3V |
| DHT11 GND | GND |
| LED | D6 |
| Buzzer | D5 |

## ⚙️ Working Principle

1. The DHT11 sensor measures the surrounding temperature.
2. NodeMCU reads the temperature value from the sensor.
3. The temperature reading is sent to the KiwisIoT dashboard.
4. If the temperature reaches or exceeds 33°C, the LED glows and the buzzer sounds.
5. If the temperature is below 33°C, the LED and buzzer remain OFF.
6. The alert status is also updated on the KiwisIoT dashboard.

## 📊 KiwisIoT Dashboard

| Channel | Description |
|---|---|
| Channel 0 | Temperature (°C) |
| Channel 1 | Alert Status (0 = Normal, 1 = Alert) |

## ✨ Features

- Real-time temperature monitoring.
- Remote temperature visualization.
- Automatic high-temperature detection.
- LED and buzzer alert indication.
- IoT-based status monitoring.

## 📚 Applications

- Smart room temperature monitoring.
- Environmental monitoring systems.
- Laboratory temperature monitoring.
- Smart building applications.
- Temperature alert systems.

## 🚀 Future Enhancements

- Mobile notifications for high-temperature alerts.
- Data logging and historical temperature analysis.
- Multiple temperature monitoring points.
- Adjustable temperature threshold through an IoT dashboard.

## 📖 Learning Outcomes

- Understanding DHT11 sensor interfacing.
- Learning digital output control using NodeMCU.
- Understanding automatic alert systems.
- Learning IoT communication using KiwisIoT.
- Integrating sensors and output devices.

## 👨‍💻 Developed Using

NodeMCU ESP8266 | DHT11 | Arduino IDE | KiwisIoT | LED | Buzzer

---
