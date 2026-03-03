# 📡 RFID Attendance System (IoT Based)

## 👨‍💻 Developer
Muhammad Talha Iftikhar

## 📌 Project Overview
This project is a complete IoT-based RFID Attendance Management System using NodeMCU (ESP8266) / ESP32, RFID module, LCD display, and a PHP-MySQL web server.

The system reads RFID card UID, sends it to a local server using HTTP protocol, and records Check-IN / Check-OUT attendance in a database.

---

## 🛠 Technologies Used

### Embedded Side:
- Arduino IDE
- ESP8266WiFi / WiFi.h
- HTTPClient
- SPI Communication
- I2C LCD

### Backend:
- PHP
- MySQL
- Apache (XAMPP)

---

## 🔌 Hardware Components
- NodeMCU (ESP8266)
- ESP32 (Optional version included)
- RFID Reader Module
- 16x2 LCD (I2C)
- Buzzer
- LEDs
- Power Supply

---

## ⚙️ Features
- RFID Card Detection
- Automatic Check-IN / Check-OUT
- WiFi Auto Reconnection
- LCD Display Feedback
- Buzzer Notification
- HTTP Communication with Server
- Database Logging

---

## 🗄 Database Setup
1. Install XAMPP
2. Import `rfidattendance.sql` into phpMyAdmin
3. Place `rfidattendance` folder inside `htdocs`
4. Update your IP address inside Arduino code

---

## 🚀 How It Works
1. User scans RFID card
2. UID is captured by NodeMCU
3. HTTP GET request sent to server
4. Server checks database
5. Returns:
   - login + username
   - logout + username
6. LCD displays result

---

## 📷 Future Improvements
- Cloud deployment
- Mobile App integration
- Face recognition integration
- Admin dashboard improvements

---

## 📜 License
This project is for academic and portfolio purposes.
