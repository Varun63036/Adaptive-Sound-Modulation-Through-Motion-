# Adaptive-Sound-Modulation-Through-Motion-

This Python project allows you to **control your system volume using hand gestures**. 

## How it works
- Tracks **thumb and index finger** using a webcam.
- Calculates the **distance between thumb and index fingertip**.
- If fingers move apart → **volume increases**.
- If fingers come closer → **volume decreases**.
- Visualizes hand landmarks and the distance line in real-time.

## Requirements
- Python 3.x
- OpenCV
- Mediapipe
- PyAutoGUI

## How to Run
1. Install dependencies:
    
    pip install -r requirements.txt
    
2. Run the program:
    bash
    python sound_control.py
  
3. Press **ESC** to exit.
