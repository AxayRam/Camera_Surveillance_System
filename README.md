Camera Surveillance System
IoT-Based Motion Sensor Camera Surveillance System
With Telegram Control using ESP32-CAM
Welcome to our innovative surveillance system project! This system offers real-time security, smart automation, and remote access using cost-effective components including ESP32-CAM, PIR sensor, and Telegram Bot API.

Project Overview
In today's world, the demand for intelligent and cost-effective surveillance systems is growing rapidly. This project demonstrates a complete solution that:

Detects motion using PIR sensor

Captures images via ESP32-CAM

Sends alerts and photos to Telegram instantly

Monitors temperature and humidity with DHT11 sensor

Controls devices like lights using relay module

The system is built with embedded IoT technology and supports two-way communication via Telegram, eliminating the need for traditional CCTV monitoring systems.

Hardware Components
ESP32-CAM (with OV2640 Camera)

PIR Sensor (Motion Detection)

DHT11 Sensor (Temperature & Humidity)

Relay Module (for controlling lights/gate)

FTDI Programmer (for uploading code)

Software & Technologies
Arduino IDE

Telegram Bot API

Key Libraries:

WiFi.h

esp_camera.h

UniversalTelegramBot.h

ArduinoJson

DHT.h

System Architecture
The ESP32-CAM serves as the core processing unit, with peripheral components connected to GPIO pins for sensing, control, and communication. The Telegram Bot functions as both remote control interface and notification platform, enabling seamless two-way interaction.

Key Features
Motion-triggered image capture

Instant image delivery via Telegram

Real-time environmental monitoring

Remote light control capability

WiFi-connected autonomous operation

Cost-effective surveillance solution

Experimental Results
Successfully captured and delivered images with minimal latency

Accurate motion detection with minimal false triggers

Real-time command interaction via Telegram platform

Stable system performance under varying environmental conditions

Reliable remote access and control functionality

Research Documentation
For detailed system design, implementation analysis, performance metrics, and future scope, please refer to our comprehensive research paper included in this repository.

Development Team
Axay Ram – axay19392@gmail.com
Anurag Purohit – er.apurohit@gmail.com

Bachelor of Engineering Students
Vishwakarma Government Engineering College, Ahmedabad

Future Enhancements
Live video streaming capability

Cloud storage integration for archival

AI-powered threat detection algorithms

Multi-camera system integration

Advanced notification systems

Power optimization features

Technical Specifications
Microcontroller: ESP32-CAM

Image Sensor: OV2640 (2MP)

Connectivity: WiFi 802.11 b/g/n

Motion Detection: PIR Sensor

Environmental Sensing: DHT11

Control Interface: Relay Module

Communication Protocol: Telegram Bot API

Installation & Setup
Clone this repository

Install required Arduino libraries

Configure WiFi credentials in the code

Set up Telegram Bot and obtain API token

Upload code to ESP32-CAM using FTDI programmer

Assemble hardware components as per circuit diagram

Test system functionality

Applications
Home security systems

Office surveillance

Industrial monitoring

Remote property management

Smart city infrastructure

Educational institution security

Connectivity
For technical discussions, collaboration opportunities, or project feedback, please feel free to connect with the development team.
