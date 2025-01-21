# Real-Time Human Pose Estimation using MediaPipe Pose

This project demonstrates a simple implementation of a real-time human pose estimation system using Google's MediaPipe library. The code can process both videos and images to detect and visualize body landmarks.

## Features

- **Video Processing**: Detect and overlay body landmarks on each frame of a video file.
- **Image Processing**: Detect and overlay body landmarks on a single image.
- **Output Video Re-encoding**: The processed video is re-encoded into a widely supported MP4 format for compatibility.
- **Visualization**: Display processed images with detected landmarks.

## Requirements

- Python 3.x
- MediaPipe
- OpenCV
- Matplotlib
- FFmpeg (for video re-encoding)

## Setup

1. Clone this repository or copy the code to your local system.
2. Install the required dependencies:
   ```bash
   pip install mediapipe opencv-python matplotlib
