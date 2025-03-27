# Volume-Control
Volume Control-AI is an OpenCV-based project that enables real-time volume adjustment using hand gestures. By utilizing computer vision techniques, this project allows users to increase, decrease, and mute volume dynamically with simple hand movements.

Features

🔊 Gesture-Based Volume Control: Adjust your system's volume without touching a button!

✋ Hand Tracking in Real-Time: Detects hand movements instantly.

📉 Smooth Volume Adjustment: No abrupt jumps—just seamless control.

🔲 Bounding Box Overlay: Highlights hand position and movement.

🚀 Fast and Efficient Processing: Works with minimal lag for a smooth experience.

Technologies Used

🐍 Python

📷 OpenCV

🔢 NumPy

🤖 MediaPipe (for accurate hand tracking)

🎛 PyCaw (for controlling system volume)

Installation

Clone the repository:

git clone https://github.com/your-username/Volume-Control-AI.git
cd Volume-Control-AI

Install dependencies:

pip install opencv-python numpy mediapipe pycaw

Usage

Run the script:

python volume_control.py

Move your hand up or down to adjust the volume.

Use a special gesture to mute or unmute the sound.

How It Works

📸 The webcam captures a live video feed.

✨ OpenCV and MediaPipe detect the hand and track its movement.

🎛 PyCaw adjusts the system volume based on the detected hand position.

🔊 The system smoothly increases or decreases volume accordingly.

![image](https://github.com/user-attachments/assets/6142553e-6678-47b9-a761-57ffc480b4d8)


