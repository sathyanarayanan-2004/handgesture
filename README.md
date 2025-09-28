# Hand Gesture Recognition System

A real-time hand gesture recognition system using **OpenCV**, **MediaPipe**, and **PyAutoGUI**.  
It allows users to control keyboard actions (e.g., arrow keys, space, etc.) with simple hand gestures.

---

## 🚀 Features
- Detects a single hand using MediaPipe.
- Recognizes **finger counts (1–5)** as gestures.
- Maps gestures to keyboard actions:
  - **1 Finger** → Right Arrow
  - **2 Fingers** → Left Arrow
  - **3 Fingers** → Up Arrow
  - **4 Fingers** → Down Arrow
  - **5 Fingers** → Space + H

---

## 🛠️ Tech Stack
- **Python**
- **OpenCV** – video capture & image processing
- **MediaPipe** – hand tracking and landmark detection
- **PyAutoGUI** – simulate keyboard key presses

---

## 📂 Project Structure
hand-gesture-recognition/
│
├── hand_gesture.py # Main Python script
├── requirements.txt # Dependencies
└── README.md # Project documentation
