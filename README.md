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

## 🌐 Wi-Fi Based Control System

This robot car features a wireless control system powered by the ESP32 microcontroller. Here's how it works:

### System Architecture

1. **ESP32 Wireless Communication**  
   The ESP32 module serves as the brain of the robot, providing built-in Wi-Fi capabilities for wireless communication. It creates its own access point or connects to an existing Wi-Fi network.

2. **Web Interface**  
   The ESP32 hosts a web-based control interface directly on the device. No external server or internet connection is required - the interface is served from the robot itself.

3. **Command Transmission**  
   Movement commands are sent from the user's device to the ESP32 via HTTP requests or WebSocket messages, ensuring real-time control with minimal latency.

4. **Multi-Platform Control**  
   Users can control the robot using any smartphone, tablet, or computer with a web browser, as long as the device is connected to the same Wi-Fi network as the robot.

### Control Flow


### Features
- ✅ No internet connection required (local network only)
- ✅ Cross-platform compatibility (works on any device with a browser)
- ✅ Real-time control with low latency
- ✅ Easy to connect and use

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
