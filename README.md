# Home-Security-System
A smart home security system prototype using Arduino UNO, PIR sensor, buzzer, and LCD display to detect motion and provide real-time alertsl

# 🏠 Smart Home Security System Using Arduino UNO

https://img.shields.io/badge/Arduino-UNO-blue?style=for-the-badge&logo=arduino
https://img.shields.io/badge/C++-Code-green?style=for-the-badge&logo=cplusplus
![License](httpslds.io/badge/License-MIT-green?style=for-the-badge
https://img.shields.io/badge/Status-Prototype-brightgreen?style=for-the-badge

---

## 📌 Objective
To develop a **smart home security system** that:
- Detects motion near doors or windows
- Alerts users via buzzer or alarm
- Displays real-time system status on an LCD screen

---

## 🛠️ Components Used
- Arduino UNO
- PIR Motion Sensor
- Ultrasonic Sensor *(optional for distance-based detection)*
- IR Sensor *(optional for door sensor)*
- Buzzer
- 16x2 LCD Display *(with I2C module preferred)*
- LEDs *(for status indication)*
- Jumper wires, Breadboard, Power supply

---

## 🔍 Methodology
1. **Sensor Integration**
   - PIR sensor for motion detection
   - IR or Ultrasonic sensor for door/window activity
2. **Alert System**
   - Activate buzzer and LEDs when intrusion is detected
   - Display warning messages on LCD
3. **Microcontroller Logic**
   - Arduino processes sensor inputs and triggers outputs
   - Timing logic to avoid false alarms
4. **Testing & Optimization**
   - Simulate intrusions and measure responsiveness
   - Tune sensor sensitivity and timing

---

## ✅ Expected Outcomes
- Detect unauthorized entry
- Visual and audible alerts
- Real-time monitoring on LCD display

---
📂 Project Structure
HomeSecuritySystem/
├── Proposal.pdf          # Detailed project proposal
├── ArduinoCode.ino       # Main Arduino sketch
├── README.md             # Documentation
└── assets/               # Images or diagrams


🔮 Future Enhancements

Mobile app integration
SMS/email alerts
Camera module for image capture
IoT-based remote monitoring


👨‍💻 Author
Rigen Das
GitHub: https://github.com/rigen1234/Home-Security-System
Contact: rigendas_cse30d@portcity.edu.bd
