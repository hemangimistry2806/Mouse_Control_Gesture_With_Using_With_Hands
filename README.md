# 🚀 Virtual Hand-Gesture Mouse Control (AI + OpenCV + MediaPipe)

A powerful hand-gesture-based virtual mouse system using **MediaPipe**, **OpenCV**, and **PyAutoGUI**.  
Control your computer cursor using **just your hand** — no sensor, no gloves, no expensive hardware.

This project is perfect for Computer Vision learners, AI enthusiasts, or anyone who wants to feel like Tony Stark (or a Super Saiyan 😤).

---

## 📸 Demo Screenshot
![Hand Tracking Demo](hands-points.png)

## 🖥️ Terminal Output
![Terminal Demo](terminal-output.png)


---

# ✨ Features

- 🖱️ **Cursor Movement** → Controlled by midpoint of **Index + Middle** finger  
- 👆 **Left Click** → Thumb touches Index finger  
- 👉 **Right Click** → Thumb touches Middle finger  
- ✊ **Exit Program** → Hold a closed fist for 2 seconds  
- 🧘 Super-smooth motion using:
  - Jitter reduction  
  - Movement smoothing  
  - Boundary control box  
- ⚡ Optimized specifically for **i5-level laptops**  
- 🧠 Uses powerful MediaPipe hand landmark detection  

---

# 📦 Requirements

Install the required Python libraries:

```bash
pip install opencv-python mediapipe pyautogui numpy
