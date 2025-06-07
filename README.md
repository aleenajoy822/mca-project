# Real-Time Emotion Detection

This project captures webcam video and detects the dominant facial emotion in real-time using **DeepFace**. It draws bounding boxes around faces and displays the detected emotion along with a sentiment indicator (positive, neutral, or negative).

## Features

- Real-time face detection via webcam
- Emotion classification into 7 categories: happy, surprise, neutral, sad, angry, disgust, fear
- Sentiment mapping with emojis
- FPS display for performance monitoring
- Built using Python, OpenCV, and DeepFace

## Files

- `app.py` - User interface to capture webcam feed and display emotion detection using Tkinter.
- `emotion_detector.py` - Emotion detection logic using DeepFace library.

## Requirements

- Python 3.6+
- OpenCV
- DeepFace
- NumPy
- Pillow (for Tkinter image display)

Install dependencies using:

```bash
pip install opencv-python deepface numpy pillow
