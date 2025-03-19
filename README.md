# Multi-functional-Autonomous-Robot
to be completed
## Heading 2
text


# Testing
# 🤖 MEAM5100 Final Project - Autonomous Competition Robot

## 🏆 Project Overview  
This project was developed as part of the MEAM5100 course at the University of Pennsylvania. The objective was to build an autonomous robot capable of **detecting and interacting with various objects** in a competitive environment. The robot was designed to **identify and transport trophies, push obstacles, and navigate autonomously** using a combination of **sensor fusion, motor control, and computer vision**.

---

## 🔥 Key Features  
✔️ **Trophy Sensing & Classification** (Real vs. Fake) using **IR Sensors**  
✔️ **Wall Following** using **Time-of-Flight (TOF) Sensors**  
✔️ **Autonomous Object Transport** (Trophy & Police Car Handling)  
✔️ **Precision Motor Control** with **Encoders & PID**  
✔️ **Beacon Tracking** via **Infrared Phototransistors**  
✔️ **Position Estimation & Navigation** with **Vive Sensor & UDP Communication**  
✔️ **ESP32 WROOM-Based Controller** with **Wireless Communication (ESPNow + UDP)**  

---

## 🛠️ Technologies & Components Used  

### **🔌 Hardware Components**
- **ESP32-WROOM** (Main MCU)  
- **4S Lipo Battery** (Power Supply)  
- **Motor-Wheel Set** (Upgraded for high torque)  
- **L298n Motor Driver**  
- **VL53L0X TOF Sensors** (Wall Following)  
- **TLV272 Op-Amps** (IR Signal Processing)  
- **PD70-01C Infrared Photodiode** (Beacon Tracking)  
- **MG996 Servo Motors** (Gripper System)  
- **Custom 2-Layer Chassis** (Optimized for Stability & Space Utilization)  

### **💻 Software & Algorithms**
- **C++ (Arduino)** - Microcontroller Programming  
- **PID Controller** - Motor Speed Control  
- **ESPNow & UDP Communication** - Wireless Data Exchange  
- **HTML Web Interface** - Remote Robot Control  
- **Vive Sensor Data Processing** - Object Localization  
- **TOF Sensor Calibration** - Wall-Following Algorithm  

---

## 📂 Project Structure  
```bash
MEAM5100-Competition-Robot/
│── docs/             # Reports, schematics, and diagrams
│── firmware/         # Arduino/ESP32 Code for robot control
│── hardware/         # CAD models, PCB designs
│── software/         # Python/C++ scripts for simulation & analysis
│── tests/            # Test scripts and performance logs
│── LICENSE           # Open-source license
│── README.md         # Main project description
│── CONTRIBUTING.md   # How to contribute
│── .gitignore        # Ignored files
