# IoT-Smart-Parking-System

## Overview
The **Smart Parking Dashboard** is an IoT-based system designed to monitor and manage parking spaces efficiently in real-time. It combines **ESP32 microcontroller**, **RFID-based vehicle detection**, **ultrasonic and IR sensors**, and **Firebase Realtime Database** to provide a modern, automated parking solution.

## Key Features
- **Real-Time Slot Monitoring:** Each parking slot is monitored for vehicle presence using RFID and ultrasonic sensors.  
- **Live Dashboard:** Firebase updates allow live visualization of parking slot availability, accessible from any device.  
- **Local Display:** An LCD (16x2) shows the status of slots locally for onsite users.  
- **Indicators:** LEDs and optional servos can indicate slot occupancy or control gates.  
- **Automatic Detection:** Entry and exit sensors track vehicles entering and leaving, updating the system automatically.  
- **Scalable Design:** Can handle multiple parking slots and can be integrated into larger smart city solutions.

## Components Used
- **ESP32** – Main microcontroller  
- **RFID Reader & Tags** – Vehicle identification  
- **Ultrasonic Sensors (HC-SR04)** – Detect vehicle presence  
- **IR Sensors** – Detect entry and exit  
- **LCD 16x2 (I2C)** – Local display of slot status  
- **LEDs / Buzzer** – Visual/audio indicators  
- **Firebase Realtime Database** – Cloud storage and live updates  
- **Servo Motors (Optional)** – Gate control

## System Workflow
1. Vehicle arrives at the parking slot.  
2. RFID tag or ultrasonic sensor detects the vehicle.  
3. ESP32 updates the slot status in Firebase.  
4. Dashboard reflects availability in real-time.  
5. Local LCD and LEDs show the slot status.  
6. Optional servo gates operate based on availability or rules.

## Applications
- Parking management in offices, malls, and public areas  
- Smart city parking solutions  
- Real-time monitoring for automated parking systems

## Author
**Anzir Rahman Khan**  
**Mehraj Hossain Mahi**  
**Mobashsher Hasan Anik**  
Daffodil International University, Bangladesh  
