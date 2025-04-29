# Two-Wheeled Balancing Robot Simulation

## Overview
This project involves designing and building a **Two-Wheeled Self-Balancing Robot** to transport water bottles autonomously in an office environment. The robot uses a combination of a **PID control system**, **MPU6050 IMU sensor**, **ultrasonic sensors**, and a **Bluetooth interface** for stability and navigation.

The goal is to automate the distribution of water bottles, improving efficiency and reducing manual effort.

## Features
- Real-time self-balancing using PID algorithm
- Obstacle detection and autonomous stop
- Compact and lightweight design
- Payload support up to 1 kg (2 bottles)
- User-friendly loading interface
- Emergency stop function
- Bluetooth control for debugging and manual override

## Technologies Used
- Arduino (ESP32 / Uno)
- MPU6050 (Accelerometer + Gyroscope)
- Ultrasonic Sensor (Obstacle Detection)
- IR Sensors (Path Tracking)
- Bluetooth Communication (Debugging & Control)
- MATLAB (Requirement validation and PID simulation)
- SolidWorks (CAD Modeling)

## Hardware Specifications
| Component | Description |
|:----------|:------------|
| Controller | Arduino UNO |
| Sensors | MPU6050, HC-SR04 (Ultrasonic), IR Sensor |
| Motors | DC Geared Motors with Encoders |
| Frame | Acrylic or Metal Chassis |
| Battery | 12V Lithium-ion battery (17Ah sizing) |

## File Structure
two-wheeled-balancing-robot-simulation/
│
├── README.md
├── code/
│    ├── balancing_robot.ino
│    └── mpu6050_init.ino
│
├── docs/
│    ├── project_report.pdf
│    ├── conceptual_design.jpg
│    ├── control_system_diagram.jpg
│
├── cad_models/
│    ├── chassis_design.png
│    ├── container_mount.png
│
└── circuit/
     └── wiring_diagram.png


## How to Run
1. Upload the Arduino Code (`balancing_robot.ino`) to your Arduino.
2. Calibrate the MPU6050 sensor.
3. Assemble the robot frame and wire up the motors and sensors as per the circuit diagram.
4. Power the system with a 12V battery.
5. Tune the PID constants (`Kp`, `Ki`, `Kd`) for optimal balancing.
6. Test the robot on flat ground, then gradually introduce obstacles.


## Future Improvements
- Add LIDAR for better mapping and navigation.
- Integration with ROS2 for full autonomous path planning.
- Add WiFi remote monitoring and control.

## Authors
- Manikant Binkadakatti – Final Year Automation & Robotics Engineer, KLE Technological University

---

### 🚀 Feel free to fork, improve, and contribute!
