# 🎛️ Gesture-Based Volume Control using OpenCV, MediaPipe, CVZone & Pycaw

This project implements a real-time hand gesture recognition system that controls the system volume using a webcam. The system detects specific hand gestures and maps them to volume levels, offering a natural and touchless way to interact with your computer.

## ✨ Features

- Real-time hand tracking using MediaPipe and CVZone
- System volume control based on finger distance (thumb ↔️ index)
- Simple and user-friendly Python implementation
- Works with any webcam
- Runs on Windows OS (via Pycaw for volume control)

## 🛠️ Technologies Used

- **Python 3**
- **OpenCV** – Video capture and image processing
- **MediaPipe** – Hand landmark detection
- **CVZone** – Simplified wrapper for MediaPipe
- **Pycaw** – Python Core Audio Library to control system volume (Windows only)

## 🖥️ System Requirements

- Windows OS
- Webcam (built-in or external)
- Python 3.7+
- pip (Python package installer)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/gesture-volume-control.git
   cd gesture-volume-control
