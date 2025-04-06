# 🤖 Line Following Robot

A simple and efficient **Line Following Robot** designed to autonomously navigate along a defined path using infrared (IR) sensors and a microcontroller.
This project demonstrates the basics of robotics, automation, and embedded systems.

## 📌 Objective

To design and build a robot that can detect and follow a black or white line on the ground using sensor feedback and motor control logic.

## 🧰 Components Used

- **Microcontroller:** Arduino Uno
- **Sensors:** IR sensor module (typically 2 or 3 units)
- **Motors:** DC geared motors (x2)
- **Motor Driver:** L298N or L293D
- **Chassis:** 2-wheel or 4-wheel base with caster
- **Power Supply:** Li-ion or 9V batteries
- **Wires, Connectors, Breadboard or PCB**

## ⚙️ Working Principle

1. **IR Sensors** detect the difference in reflectivity between the black line and the white background.
2. Based on sensor input, the Arduino adjusts motor speed and direction:
   - If the line is centered → move forward
   - If the line is towards the left → turn left
   - If the line is towards the right → turn right
3. Continuous real-time feedback loop ensures the robot follows the path.

## 🧠 Logic Overview (Pseudocode)

