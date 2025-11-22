# Robot Overview 🦾

This document provides an overview of the main hardware components used in the AI Crawling Bot. Each part is essential for the robot’s operation and is shown below with a visual reference.

## 🌐 Language Versions
- [English](robot-overview.md)
- [فارسی (Persian)](robot-overview.fa.md)

---

## 0. The Power Button 🔘
The most important part of the robot is the power button. It is used to turn on and off the robot. The power button is located on the side of the robot, at the bottom of the battery compartment.
And make sure to turn it off when you are not using the robot to save battery life.

<img src="images/power-btn.jpeg" alt="Power Button" height="300"/>
<img src="images/power-btn-0.jpeg" alt="Power Button Close-up" height="300"/>

---

## 1. Microcontroller (ESP32) with Micro-USB Port 🧠🔌

The ESP32 is the brain of the robot, responsible for running the AI logic and controlling all other components. It connects to your computer via a micro-USB port for programming and power.

<img src="images/esp32-nodemcu.jpg" alt="ESP32 Microcontroller" height="300"/>
<img src="images/esp32-on-table.jpg" alt="ESP32 on Table" height="300"/>

---

## 2. I2C Character LCD 🖥️

This display module shows information such as sensor readings, status messages, or debugging output. It communicates with the ESP32 using the I2C protocol.

<img src="images/I2C-LCD.jpg" alt="I2C Character LCD" height="300"/>
<img src="images/lcd-in-robot.jpeg " alt="I2C Character LCD in Robot" height="300"/>
<img src="images/robot-lcd.jpg" alt="Robot with I2C Character LCD" height="300"/>

---

## 3. SRF-05 Ultrasonic Distance Sensor 📏🦇

The SRF-05 sensor measures the distance to obstacles in front of the robot, enabling it to navigate and avoid collisions.

<img src="images/robot-srf-front.jpeg" alt="SRF-05 Ultrasonic Distance Sensor" height="300"/>
<img src="images/srf05.jpg" alt="SRF-05 Ultrasonic Distance Sensor" height="300" width="250" />
<img src="images/pure-boards.jpeg " alt="SRF-05 Ultrasonic Distance Sensor on Pure Boards" height="300" width="350"/>

---

## 4. Servo Motors (2x) ⚙️🤖

Two servo motors are used to control the movement of the robot’s legs or wheels, allowing it to crawl or steer.
The MG90S micro servo is a common choice for this purpose due to its compact size and sufficient torque.
> **Note:** Micro servos like the MG90S typically rotate within a range of 0° to 180°. Sending control signals outside this range may damage the servo or cause erratic behavior.

<img src="images/micro-servo-mg90s.jpg" alt="Micro Servo MG90S" height="300"/>
<img src="images/microservo-on-robot.jpg" alt="Micro Servo on Robot" height="300"/>

---

## 5. Battery 🔋

A rechargeable battery provides portable power to the robot, enabling it to operate without being tethered to a computer.

<img src="images/battery-on-robot.jpeg" alt="Battery on Robot" height="300"/>

---

## 6. Control Charge Module (USB Type-C) ⚡🔌

This module allows the battery to be safely charged using a USB Type-C cable, making recharging convenient and safe.

<img src="images/control-charge.jpg" alt="Control Charge Module" height="300"/>
<img src="images/charge-module-on-robot.jpg" alt="Control Charge Module on Robot" height="300"/>

---

## 7. Important Ports 🛠️

The robot features two essential ports:

- **Micro-USB Port:**  
    Used for programming the ESP32 microcontroller and providing power during development. Connect this port to your computer to upload code or debug the robot.

- **USB Type-C Port:**  
    Dedicated to charging the robot’s battery via the control charge module. Use a standard USB Type-C cable to recharge the battery safely.

<img src="images/ports.jpeg" alt="Micro-USB and Type-C Ports" height="300"/>

These ports serve different purposes—ensure you use the correct port for programming or charging to avoid hardware issues.

---

##  8. Body 🦿
The robot's body is custom-designed and 3D printed to securely house all electronic components and provide structural support. Its lightweight and durable construction ensures stability during movement and protects internal hardware.

<img src="images/body-0.jpeg" alt="3D Printed Robot Body Top View" height="300"/>
<img src="images/body-1.jpeg" alt="3D Printed Robot Body Side View" height="300"/>
<img src="images/body-2.jpg" alt="Fully Assembled Robot Body" height="300"/>

---

## 📹 Watch the Robot in Action

For a detailed demonstration of the AI Crawling Bot and its components, watch the following video:

[▶️ AI Crawling Bot Overview (Google Drive)](https://drive.google.com/file/d/1TIa0ktaaaPdPyBMpJnHhDxLsFk6jlDfr/view?usp=share_link)

[🚀 AI Crawling Bot Overview (Telegram)](https://t.me/ai4032_iust/126)
