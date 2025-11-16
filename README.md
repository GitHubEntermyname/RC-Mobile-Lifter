# 🚗 RC Mobile Lifter

### 📌 Overview
The **RC Mobile Lifter** is a remote-controlled car equipped with a robotic lifting arm.  
It is controlled via a **mobile phone** using Bluetooth, combining mobility with manipulation capabilities.  
This project demonstrates the integration of mechanical design, embedded systems, and wireless communication.

### ⚙️ Features
- Remote control via mobile phone (Bluetooth HC-05)  
- 4-wheel drive with DC motors  
- Robotic arm powered by servo motors  
- Ability to lift and move small objects  
- Powered by a 9–12V battery  

### 🛠️ Components
- DC Motors + Wheels (4x) + Chassis  
- Motor Driver Shield (L293D)  
- Arduino UNO  
- Servo Motors  
- Bluetooth Module (HC-05)  
- Jumper wires  
- Battery (9–12V)  

### 📂 Files
- `src/Code.ino` → Arduino sketch controlling motors and servos  
- `images/` → Project photos (assembly and final build)  
- `.gitignore` → ignored files configuration  
- `.gitattributes` → repository attributes  
- `README.md` → project documentation  

### 🚀 How It Works
- The mobile phone connects to the Arduino via Bluetooth (HC-05).  
- Commands are sent from the phone app to control movement and lifting.  
- The robotic arm uses servo motors to pick up and place objects.  
- The motor driver shield (L293D) controls the DC motors for navigation.  

### 🙌 Acknowledgment
Developed as part of my **Mechatronics Engineering projects**.  
Demonstrates practical application of **Arduino programming, robotics, and wireless control systems**.
