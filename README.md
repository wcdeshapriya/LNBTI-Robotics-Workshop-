#  IoT & Robotics Introductory Workshop

## Overview
This document summarizes the Introductory Workshop on Robotics and IoT, conducted to provide foundational knowledge and hands-on exposure to students on modern embedded systems, automation, and connected technologies.

## Workshop Agenda

### Key Focus Areas
- Introduction to Robotics and IoT technologies  
- Requirements for robotics systems  
- Applications of Robotics and IoT  
- Career guidance in Robotics  
- Hands-on practical sessions  
---

## What is IoT?
IoT (Internet of Things) refers to a network of interconnected devices that communicate and exchange data over the internet.

These systems include:
- Sensors (data collection)
- Communication modules (data transfer)
- Actuators (control and automation)
---
---

## Sensors Used in Robotics / IoT
- PIR Sensor  
- IR Sensor  
- Ultrasonic Sensor  
- Accelerometer  
- Magnetic Sensor  
- Gas Sensor  
- Temperature Sensor  
- Humidity Sensor  

## Actuators
- LED  
- LCD Display  
- Motors  
- Buzzer  
- Relay  

## Controllers
- PIC Microcontroller  
- Atmel Microcontroller  
- Intel Microcontroller  
- PLC Systems  
- Raspberry Pi  
---

## Robot Systems
Robot arms are mechanical devices designed to simulate human arm movements and perform automated tasks.

## Robotics Applications
- Assembly line robots  
- Welding robots  
- Painting robots  
- Healthcare surgical robots  
- Robotic vacuum cleaners  
---

## IoT Applications
- Smart homes  
- Industrial automation  
- Agricultural monitoring  
- Healthcare systems  
- Smart city solutions  
---

## Microcontroller Platforms
- Arduino Boards (UNO, Mega, Nano, etc.)  
- ESP8266 / ESP32  
- Raspberry Pi  
- PLC Systems  
---
## Arduino software download:

Arduino IDE software for Windows: https://downloads.arduino.cc/arduino-ide/arduino-ide_latest_Windows_64bit.exe

Arduino IDE software for macOS: https://downloads.arduino.cc/arduino-ide/arduino-ide_latest_macOS_64bit.dmg

## Arduino Example Code (LED Blinking)
<img width="440" height="278" alt="image" src="https://github.com/user-attachments/assets/00ec1cb6-d064-4df2-a082-f9b086096871" />

Select board:
Tools--> Board--> Select board

Select port: 
Tools --> Serial Port--> COM xx


```cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
```
---

# 👨‍🏫 Author: Mr. W.C. Deshapriya

Lecturer | Software Engineer | IoT Consultant  
