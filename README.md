# 🚀 Virtual Hand-Gesture Mouse Control (AI + OpenCV + MediaPipe)

A powerful hand-gesture-based virtual mouse system using **MediaPipe**, **OpenCV**, and **PyAutoGUI**.  
Control your computer cursor using **just your hand** — no sensor, no gloves, no expensive hardware.

This project is perfect for Computer Vision learners, AI enthusiasts, or anyone who wants to feel like Tony Stark.

---

## 📸 Demo Screenshot
![Hand Tracking Demo](hands-points.png)

## 🖥️ Terminal Output
![Terminal Demo](terminal-output.png)


---

## ✨ Features
- Hand tracking using MediaPipe
- Move mouse cursor with hand movement
- Click using finger gestures
- Smooth cursor movement using interpolation
- Works on any webcam

---

## 🧠 How It Works
1. MediaPipe detects 21 hand landmarks.
2. Index fingertip coordinates are extracted.
3. Coordinates are mapped to screen size.
4. Cursor moves according to finger movement.
5. Clicks are detected using finger distance logic.

---

# 📦 Requirements

Install the required Python libraries:

## 🏃‍♂️ Run the Project
```bash
pip install opencv-python mediapipe pyautogui numpy
pip install -r requirements.txt
python Mouse.py
