# 🖱️ Virtual Mouse using Hand Gestures

## 📌 Project Overview

The Virtual Mouse project replaces a physical mouse with hand gesture control using a webcam. It detects hand movements and finger positions in real-time and converts them into mouse actions such as cursor movement and clicking.

This project is implemented using Python, OpenCV, MediaPipe, and PyAutoGUI.

---

## 🚀 Features

- Real-time hand tracking
- Cursor movement using index finger
- Left click using index + middle finger gesture
- Smooth mouse movement
- FPS (Frames Per Second) display
- No physical mouse required

---

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy
- Math module

---

## ⚙️ How It Works

1. The webcam captures live video.
2. MediaPipe detects 21 hand landmarks.
3. Finger positions are identified.
4. Hand coordinates are mapped to screen resolution.
5. PyAutoGUI performs mouse actions.

### 🎯 Gesture Controls

- 🟢 Index Finger Up → Move Cursor  
- 🟢 Index + Middle Finger Up (close together) → Left Click  

---

## 💻 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/virtual-mouse.git
cd virtual-mouse
```

### Step 2: Install Required Libraries

```bash
pip install opencv-python mediapipe pyautogui numpy
```

### Step 3: Run the Project

```bash
python virtual_mouse.py
```

---

## 🖥️ Requirements

- Python 3.x
- Webcam
- Windows / macOS / Linux

---

## 📈 Future Improvements

- Right-click gesture
- Scroll gesture
- Drag and drop functionality
- GUI for settings
- Sensitivity control customization

---

## 📚 Learning Outcomes

- Understanding of Computer Vision basics
- Real-time hand landmark detection
- Gesture recognition logic
- Mapping coordinates to screen resolution
- Practical use of automation libraries

---

## 👩‍💻 Author

Nithin Gopal Chinthala  
B.Tech CSE (AIML)  
