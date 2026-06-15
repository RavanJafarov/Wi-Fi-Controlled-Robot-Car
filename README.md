# Wi-Fi-Controlled-Robot-Car

## 📋 Overview
A Wi-Fi-based robot car controlled via a web interface hosted on an ESP32 microcontroller. Users can control the robot using a smartphone or computer connected to the same network.

## 🔧 Main Components
- **ESP32 Microcontroller** – Wi-Fi & Bluetooth enabled
- **L298N Motor Driver** – Dual H-bridge for DC motor control
- **Li-Ion Battery** – Rechargeable power source
- **DC Motors** – For movement
- **Ultrasonic Distance Sensor** – Obstacle detection

## 🎮 Control System
The ESP32 hosts a web interface that sends movement commands via HTTP requests:
- `F` – Forward
- `B` – Backward
- `L` – Left
- `R` – Right
- `S` – Stop

## 📌 Pin Configuration
| Pin | Function |
|-----|----------|
| 14  | IN1 |
| 27  | IN2 |
| 26  | IN3 |
| 25  | IN4 |

## 🚀 Getting Started
1. Install **Arduino IDE** with ESP32 board support
2. Upload the code from `src/wifi_robot_car.ino`
3. Connect to the ESP32's Wi-Fi network
4. Open the web interface in a browser and control the robot

## 📸 Gallery
Check the `images/` folder for build photos.

## 👥 Authors
- Ravan Jafarov
- Azer Aslanov
