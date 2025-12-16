# 📷 Camera Surveillance System  
## 🔒 IoT-Based Motion Sensor Camera Surveillance System using ESP32-CAM & Telegram

An intelligent IoT-based surveillance system designed to provide real-time security, smart automation, and remote monitoring using cost-effective hardware such as ESP32-CAM, PIR sensor, and Telegram Bot API. This system eliminates the need for traditional CCTV monitors by enabling instant alerts, image capture, and remote control through Telegram.

---

## 🧠 About the Project

In today’s world, the demand for low-cost and intelligent security solutions is rapidly increasing. This project demonstrates a complete embedded IoT surveillance solution that:

- Detects motion using a PIR sensor  
- Captures images using ESP32-CAM  
- Sends alerts and images instantly via Telegram  
- Monitors temperature and humidity using DHT11  
- Controls external devices such as lights or gates using a relay module  

The system supports two-way communication via Telegram, allowing users to monitor and control the system remotely from anywhere.

---

## 🔧 Hardware Used

- ESP32-CAM (with OV2640 Camera)  
- PIR Sensor (Motion Detection)  
- DHT11 (Temperature & Humidity Sensor)  
- Relay Module (Light/Gate Control)  
- FTDI Programmer (for uploading code)

---

## 💻 Software & Tools

- Arduino IDE  
- Telegram Bot API  

### Libraries Used
- WiFi.h  
- esp_camera.h  
- UniversalTelegramBot.h  
- ArduinoJson  
- DHT.h  

---

## 📐 System Architecture

The ESP32-CAM acts as the core controller of the system. Sensors and relay modules are connected through GPIO pins. The ESP32-CAM connects to WiFi and communicates with the Telegram Bot, which serves as both the notification system and remote control interface. This architecture ensures real-time monitoring, automation, and reliable performance.

---

## 📸 Features

- Motion-triggered image capture  
- Instant image delivery via Telegram  
- Real-time temperature and humidity monitoring  
- Remote control of lights or gate using relay  
- Fully automated WiFi-based IoT surveillance system  

---

## 🧪 Experimental Results

- Successfully captured and delivered images via Telegram  
- Accurate motion detection with minimal false triggers  
- Real-time interaction through Telegram commands  
- Stable system performance under varying environmental conditions  

---

## 📚 Research Paper

The complete system design, implementation details, performance analysis, and future scope are documented in our research paper.  
(Add paper link here if available)

---

## 🤝 Authors

Axay Ram  
Email: axay19392@gmail.com  

Anurag Purohit  
Email: er.apurohit@gmail.com  

B.E. Students  
Vishwakarma Government Engineering College, Ahmedabad  

---

## 🧠 Future Scope

- Live video streaming support  
- Cloud storage integration  
- AI-powered threat detection and analysis  

---

## 📬 Let’s Connect

If this project inspired you, feel free to fork the repository, star it, or share your feedback and ideas. Contributions and suggestions are always welcome.

---

## 🔖 Tags

#IoT #ESP32CAM #SurveillanceSystem #SmartSecurity #TelegramBot #EmbeddedSystems
