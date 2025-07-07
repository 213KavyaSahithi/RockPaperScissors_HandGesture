# 🖐️ Rock Paper Scissors - Hand Gesture Detection

This is a fun computer vision project that lets **two players** play **Rock, Paper, Scissors** using hand gestures captured via webcam. It uses **OpenCV** for video capture and display, and **MediaPipe** to detect hand landmarks and interpret gestures in real-time.

## 🎮 How It Works

- Uses your webcam to detect **two hands**.
- Tracks hand landmarks using **MediaPipe Hands**.
- Interprets hand gestures:
  - ✊ **Rock**: All fingers closed.
  - ✋ **Paper**: All fingers open.
  - ✌️ **Scissors**: Index and middle finger open.
- Displays countdown and shows result after both players make a gesture.

## 🛠 Requirements

- Python 3.7+
- OpenCV
- MediaPipe

## 📦 Installation

1. Clone the repository:

git clone https://github.com/your-username/rock-paper-scissors-hand-gesture.git
cd rock-paper-scissors-hand-gesture 

2. Install Dependencies:

pip install opencv-python mediapipe

3. Run the Game

python main.py

Press Q to quit the Game

## ✅ To-Do
-> Add support for single-player mode against AI
-> Improve gesture recognition robustness
-> Add GUI overlay for improved game experience