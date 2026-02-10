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

## 📷 Demo
* PARKING SYSTEM PROTOTYPE
  
<img width="471" height="419" alt="image" src="https://github.com/user-attachments/assets/fa523d43-e00a-4a7c-92da-c7b3e2618169" />

* USER INTERFACE (UI)

<img width="1179" height="613" alt="image" src="https://github.com/user-attachments/assets/5c05f8e5-f072-4dca-a1c9-789c8a3ced4e" />

* VEHICLE LICENSE PLATE CAPTURE SYSTEM AT ENTRY

<img width="1058" height="641" alt="image" src="https://github.com/user-attachments/assets/210d8086-00b7-4dd9-ac32-94af039e0cda" />

* VEHICLE LICENSE PLATE CAPTURE SYSTEM AT EXIT

<img width="1037" height="627" alt="image" src="https://github.com/user-attachments/assets/2f1527fa-28a7-4d4b-9569-bdb9767e8ad7" />

* THE SYSTEM STORES VEHICLE ENTRY AND EXIT DATA INTO A CSV FILE AND EXCEL FILE 

<img width="566" height="223" alt="image" src="https://github.com/user-attachments/assets/adaf3b94-316f-44c1-911e-1b908e512273" />

<img width="604" height="292" alt="image" src="https://github.com/user-attachments/assets/e11fcbcc-a9b0-4496-9b59-224cb370f591" />


---

## 🧠 What I Learned
- Understanding the working principle of RFID-based attendance systems
- Interfacing RFID RC522 with ESP32
- Reading and handling UID data from RFID cards
- Using RTC module to obtain real-time date and time
- Displaying system information on LCD 2004 via I2C
- Designing system logic for student attendance management
- Structuring an embedded system project and documenting it on GitHub

---

## 🚀 Future Improvements
- Add a database to store student and attendance information
- Export attendance data to Excel or Google Sheets
- Develop a web-based interface for attendance management
- Add authentication and role management (admin / user)
- Improve system reliability and error handling
- Integrate cloud services for remote data access

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
