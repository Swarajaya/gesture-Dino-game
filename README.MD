🦖 Gesture Dino Game (Webcam Controlled)

A real-time gesture-controlled Dino game built using Python, OpenCV, MediaPipe, and Pygame.
Control the dinosaur using hand gestures detected through your webcam — no keyboard required.

📁 Project Structure
gesture_dino_game/
│
├── main.py              # Main game logic (run this file)
├── requirements.txt     # Python dependencies
├── models/              # MediaPipe hand tracking model
└── venv/                # Python virtual environment

🎮 How to Play
Gesture	Action
☝️ One finger	Jump
✌️ Two fingers	Duck
✋ Open palm	Restart game
No hand	Idle

The webcam feed appears inside the game window to guide gestures.

🚀 Features

Real-time hand gesture recognition

Smooth physics-based jumping

Dynamic obstacle spawning

Live webcam preview

Score tracking

No keyboard required

Runs fully offline

🛠️ Requirements

Python 3.10

Webcam

Windows (tested)

⚙️ Installation
1️⃣ Create & Activate Virtual Environment
python -m venv venv
venv\Scripts\activate

2️⃣ Install Dependencies
pip install -r requirements.txt


⚠️ Do NOT upgrade protobuf or TensorFlow.
This project uses a stable MediaPipe configuration.

▶️ Run the Game
python main.py


The game window will open automatically.

🧠 Technologies Used

Python

OpenCV

MediaPipe

Pygame

🧩 File Overview
File	Purpose
main.py	Core game logic + gesture detection
requirements.txt	Dependency list
models/	MediaPipe hand tracking model
venv/	Python virtual environment