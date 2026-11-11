# Arduino Radar System

A real-time radar visualization project built using an **Arduino Uno**, **HC-SR04 Ultrasonic Sensor**, **SG90 Servo Motor**, and **Processing**. The system scans its surroundings by rotating the ultrasonic sensor and displays detected objects on a radar-style interface in real time.

---

## Features

* Real-time radar visualization
* Servo-controlled scanning (15°–165°)
* Live distance measurements using the HC-SR04 sensor
* Serial communication between Arduino and Processing
* Rotating radar sweep animation
* Red object detection indicator
* Green tracking lines

---

## Hardware

* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* SG90 Servo Motor
* Breadboard
* Jumper Wires
* USB Cable

---

## Software

* VS Code (C++)
* Processing

---

## How It Works

1. The servo rotates the ultrasonic sensor between **15° and 165°**.
2. The sensor measures the distance to nearby objects.
3. The Arduino sends the **angle** and **distance** data to the computer through Serial communication.
4. Processing reads the incoming data and updates the radar display in real time.
5. Detected objects are displayed as **red markers**, while the radar sweep and tracking lines visualize the scanning process.

---

## Future Improvements

* OLED display integration
* ESP32 version
* Wireless communication
* Smoother radar animation
* Multiple object tracking
* 3D radar visualization


