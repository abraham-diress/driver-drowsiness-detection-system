# Driver's Drowsiness Detection System

## Introduction
The Driver's Drowsiness Detection System is a cutting-edge tool designed to enhance road safety by detecting signs of driver fatigue and drowsiness in real-time. Utilizing advanced computer vision and machine learning techniques, this system analyzes a driver's facial features and eye movements to identify potential drowsiness, alerting them promptly to prevent accidents.

## Features
- Real-time detection of drowsiness based on facial features and eye movement.
- Visual and auditory alerts to notify the driver upon detection of drowsiness.
- Easy-to-use interface with real-time video feed.

## Getting Started

### Prerequisites
Before running the application, ensure you have the following installed:
- Python 3.8 or later
- TensorFlow 2.x
- OpenCV (cv2)
- Pygame

### Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/[your-username]/drowsiness-detection.git
   cd drowsiness-detection ```
2. **Change Directory**
   ```bash
   cd src ```
4. **Install Dependencies**
   ```bash
   pip install opencv-python
   pip install pygame
   pip install tensorflow
   pip install numpy ```

5. **Run Applicaion**
   ```bash
   python app.py ```

### Usage
Once the application starts, it will access the computer's webcam. Ensure good lighting conditions for accurate detection. The system will analyze the video feed in real-time and provide visual and auditory alerts if drowsiness is detected.

