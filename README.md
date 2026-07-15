t# ESP32-Rover-R3.
A custom ESP32-based robotic rover with a web UI, OLED expressions, and autonomous modes.
# ESP32 Rover R3 🤖

This repository contains the source code for the R3 iteration of my custom-built robotic rover. 

## Features
* **Web UI Dashboard:** Hosted on the ESP32 to control the car via Wi-Fi (Joystick, Speed Control, Sensor Toggles).
* **OLED Expressions:** I2C display providing live feedback and dynamic "facial" expressions based on sensor data.
* **Autonomous Modes:** Line following, cliff detection, and obstacle avoidance using optimized IR and Ultrasonic sensor logic.

## Hardware Components
* ESP32 30-pin CP2102
* L298N Motor Driver
* SG90 Micro Servo
* HC-SR04 Ultrasonic Sensor & IR Sensors
* I2C OLED Display
* MP1495 Buck Converter

## How to Use
1. Flash the `.ino` file to your ESP32 using the Arduino IDE.
2. Connect to the ESP32's Wi-Fi access point.
3. Open a web browser and navigate to the assigned IP address (e.g., 192.168.4.1) to access the control dashboard.
   
[Click here to view the full Project Report / Schematic](Detail_Pin_Mapping.pdf)
