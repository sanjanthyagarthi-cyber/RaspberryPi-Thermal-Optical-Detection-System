# RaspberryPi-Thermal-Optical-Detection-System
Final Year Project on Raspberry Pi-Based Thermal and Optical Detection System with Automated Targeting and Real-Time Monitoring.
# Raspberry Pi-Based Thermal and Optical Detection System with Automated Targeting and Real-Time Monitoring

This project presents an **advanced surveillance and targeting system** that integrates **thermal and optical sensing** using a Raspberry Pi 5.  
It is capable of **automated target detection, tracking, and real-time monitoring**, showcasing the potential of embedded systems in intelligent security and defense applications.

---

## 🔍 Project Overview

The system combines a **thermal sensor**, **web camera**, **servo motors**, and a **laser module** to detect, identify, and track objects automatically.  
The **Raspberry Pi 5** acts as the central processing unit, analyzing both visual and thermal data to make intelligent targeting decisions.

---

## 🎯 Key Objectives

- Design a **thermal detection and optical tracking system**.
- Integrate thermal and optical data for enhanced detection accuracy.
- Implement **automated target aiming** and **real-time monitoring** capabilities.
- Enable **remote visualization** using RealVNC.

---

## ⚙️ Hardware Components

| Component | Description |
|------------|-------------|
| **Raspberry Pi 5** | Central controller for data processing and decision-making |
| **AMG8833 Thermal Sensor** | Detects infrared heat signatures |
| **Web Camera (Zebronics Crystal Pro)** | Captures visual data for object detection |
| **Laser Module (KY-008)** | Simulates target aiming |
| **Servo Motor (SG90)** | Controls the direction of the laser module |
| **Arduino UNO R3** | Acts as motor driver to control servo motion |
| **Missile Module Prototype** | Simulated mechanism for target response |

---

## 🧠 Software Used

- **Python 3**
- **OpenCV** – for real-time image and object detection
- **Thonny IDE** – for Python development
- **Arduino IDE** – to program the Arduino motor driver
- **RealVNC Viewer** – for remote monitoring of the Raspberry Pi
- **NumPy** – for numerical computation

---

## 🧩 System Workflow

1. The **thermal sensor** detects temperature variations.
2. The **webcam** captures live video feed for object recognition.
3. **OpenCV** analyzes both sources to identify and track a target.
4. The **Raspberry Pi** sends control signals to the **Arduino**, which drives the **servo motor**.
5. The **laser module** points toward the detected target for precise aiming.
6. Real-time monitoring is available via **VNC Viewer**.

---

## 📈 Future Scope

- Integration of **machine learning** for improved object classification.
- Use of **AI-based threat recognition** for defense applications.
- Expansion to **drone-based surveillance** systems.
- Cloud-based data storage for analytics and monitoring.

---

## 👩‍💻 Project Team

- **Dhanya R Rao** – 4NN21EC012  
- **Varsha Bhat K** – 4NN21EC050  
- **Sanjan G** – 4NN22EC411  
- **Yashwanth M** – 4NN22EC413  

**Guide:** Dr. Manjula A V  
_Associate Professor & HOD, Department of ECE, NIE Institute of Technology, Mysuru_

---

## 🏫 Institution

**Visvesvaraya Technological University (VTU)**  
Department of **Electronics and Communication Engineering**  
**NIE Institute of Technology, Mysuru**  
**Academic Year:** 2024–2025

---

## 📄 Project Report

For the complete documentation, refer to the file:  
➡️ **[Final draft_merged.pdf](./Final%20draft_merged.pdf)**
