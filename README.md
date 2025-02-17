# Face Detection Using OpenCV

This project is a simple real-time face detection system using OpenCV's Haar cascade classifier. It captures video from the webcam, detects faces, and draws bounding boxes around them.

## Features
- Uses OpenCV's `haarcascade_frontalface_default.xml` for face detection.
- Processes video frames in real-time.
- Draws green bounding boxes around detected faces.
- Stops execution when the user presses the 'q' key.

## Installation

Ensure you have Python installed, then install OpenCV:
```bash
pip install opencv-python

```
## How It Works

- The script initializes OpenCV's Haar cascade classifier for face detection.
- It captures video frames from the default webcam.
- Converts the frame to grayscale and detects faces.
- Draws a green rectangle around detected faces.
- Displays the processed frames in a window.
- Press q to exit.

## Requirements
- Python 3.x
- OpenCV (cv2)

## Demo
A preview window will open, showing detected faces with green bounding boxes.
