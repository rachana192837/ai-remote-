Hand & Clap Media Controller

This Python project allows you to control media playback (like YouTube or any video player) using hand gestures and clap detection.

👏 Clap Detection: Toggle play/pause when you clap.

👈👉 Hand Gestures:

Move your hand to the left → Skip backward 5 seconds

Move your hand to the right → Skip forward 5 seconds

Features

Real-time hand gesture recognition using MediaPipe

Audio-based clap detection using SoundDevice

Works with any media player that responds to keyboard shortcuts (space, left, right)

Easy to run on a webcam-enabled system

Requirements

Python 3.8+

Libraries:

pip install opencv-python mediapipe sounddevice numpy pyautogui


A webcam for hand gesture detection

A microphone for clap detection

How to Use

Clone the repository or download the Python script.

Ensure your media player is active and ready (e.g., YouTube video in browser).

Run the script:

python hand_clap_controller.py
