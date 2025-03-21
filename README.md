# 🚀 MEAM5100 Multi-Functional Autonomous Robot

## 🏆 Overview
This project was developed as part of the **MEAM5100 - Design of Mechatronic Systems** course at the **University of Pennsylvania**. The goal was to design, build, and program an autonomous robot capable of competing in a structured game environment. The robot successfully completed navigation tasks, object detection, and interaction with game elements such as trophies and a police car.

## 🎯 Project Goals
The robot was designed to:
- **Identify and transport a real trophy** while pushing a fake trophy to the opponent's side.
- **Push a police car into the opponent's zone** to reduce their score.
- **Use infrared (IR) and Time-of-Flight (TOF) sensors** for precise object detection and wall following.
- **Implement real-time localization** using a Vive tracking system.
- **Utilize wireless communication** (ESP-NOW and UDP) for real-time position updates.

## 🛠 System Architecture
### 🔧 **Mechanical System**
- Differential drive system for stability and control.
- Reinforced chassis to handle object interactions.

### ⚡ **Electrical System**
- **ESP32-WROOM** as the primary microcontroller.
- **IR phototransistors and TOF sensors** for object detection and wall following.
- **L298N motor driver** to control dual DC motors.
- **Vive tracking sensor** for absolute positioning.

### 💻 **Software & Control**
- **State machine-based control system** to prioritize tasks.
- **PID control for motor speed regulation**.
- **ESP-NOW & UDP communication** for real-time data exchange.
- **HTML-based web interface** for manual debugging and testing.

## 📊 Key Results & Performance
- Successfully completed **trophy detection and retrieval** within 2.5 meters.
- **Police car push was successful in 80% of trials**, with minor misalignment corrections.
- **Wall-following algorithm achieved a deviation of less than 5 cm**.
- **Wireless communication maintained a stable update rate**, though packet loss occurred in high-interference environments.

## 🔮 Future Improvements
- **Adaptive PID tuning** to correct minor trajectory drift over long distances.
- **Kalman filtering for Vive tracking** to reduce jitter in position data.
- **Improved IR sensor shielding** to minimize interference from ambient light.
- **Redundant message handling for ESP-NOW** to improve data reliability.

## 📁 Repository Structure
```
📂 MEAM5100-Project
│── 📂 docs/               # Contains final report and project schematics
│── 📂 code/               # All Arduino/ESP32 source code
│── 📂 hardware/           # CAD models, mechanical drawings
│── README.md              # Project overview, discussion, and results
│── LICENSE                # Not licensed
│── .gitignore             # Ignore unnecessary files (build files, logs)
```

## 🔗 References & Resources
- **[Final Report (PDF)](https://github.com/Starfishtuna/Multi-functional-Autonomous-Robot/blob/ab96b983ff3665691ee842dd8c50d9c9f5aa7c35/docs/MEAM5100%20Final%20Report.pdf)**
- **[Video Demonstrations - Wall Following](https://youtu.be/YIY6aNa_LFA)**
- **[Video Demonstrations - Beacon Tracking](https://youtu.be/LpJzdycJREA)**
- **[Video Demonstrations - Police Car Tracking](https://youtu.be/CTSYHR0mnvY)**

## 👥 Team Members
- **Chen Hsin Chiang**
- **Xiangyu Han**
- **Yipeng Zhang**

## 📜 License
This project is not licensed for public use. Redistribution, modification, or usage of any part of this project is not permitted without explicit authorization from the team.

