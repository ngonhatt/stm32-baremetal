# 📚 Student Attendance System using RFID

## 📌 Overview
This project implements a **Student Attendance System** using RFID technology.
Students scan their RFID cards to record attendance automatically.
The system displays information on an LCD and stores attendance data for later processing.

This project is developed as a **course project**.

---

## 🛠️ Hardware Components
- ESP32 Development Board
- RFID RC522 Module
- LCD 2004 (I2C)
- RTC DS1307
- RFID Cards
- Power Supply & Connecting Wires

---

## ⚙️ System Features
- Student identification using RFID cards
- Automatic attendance recording
- Real-time clock for date & time
- Display status and information on LCD
- Data storage for attendance tracking
- Export attendance data (Excel / Google Sheets – future work)

---

## 🧠 System Architecture
- ESP32 handles RFID scanning and logic
- RTC provides real-time timestamp
- LCD displays system status
- Attendance data is stored and processed

---

## 📂 Project Structure
```text
student-attendance-system/
├── src/
│   ├── main.c
│   ├── rfid.c
│   ├── lcd.c
│   └── rtc.c
├── inc/
│   ├── rfid.h
│   ├── lcd.h
│   └── rtc.h
├── README.md
