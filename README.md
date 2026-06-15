# Patient Tracking System

A Jetson Orin Nano-based patient monitoring system that **uses YOLO pose estimation, servo tracking, and an AI voice assistant to detect patient behavior and respond in real time**.

---

## 🕹️😐 Overview

This project allows you to **monitor a patient remotely using a camera that physically follows them**, while automatically detecting possible pain or emergencies.

---

## 🧠 Features

- 🎯 Uses YOLOv8 to track patient pose
- 🎥 Live camera stream with OpenCV
- 🤖 AI assistant (Ollama) that talks to the patient
- 🔊 Text-to-speech voice system (pyttsx3)
- ⚙️ Servo motor tracking (Pan + Tilt)
- 🧠 Behavior detection:
  - Fall detection  
  - Head pain  
  - Stomach pain  
  - Back pain  
- ⏰ Scheduled reminders
- 📊 Event logging system
- 📧 Email reporting
- 🔇 Error suppression (clean terminal output)

---

## 📦 Hardware Requirements

- Jetson Orin Nano  
- USB Camera (e.g., Logitech C270)  
- PCA9685 Servo Driver  
- 2x MG995 Servos  
- External power supply for servos  

---

## 🧰 Software Requirements

Before installing anything, make sure you're in a virtual environment:

```bash
# clone the repository
git clone https://github.com/ThiagoSun1/patient-tracking

# install virtualenv
sudo apt install virtualenv

# create virtual environment
virtualenv venv

# activate virtual environment
source venv/bin/activate
