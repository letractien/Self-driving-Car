# Self-driving Car Project

## Overview
This project involves the development of a self-driving car model capable of line detection, obstacle avoidance, and traffic sign recognition. The model uses computer vision and AI techniques to navigate safely and respond to road conditions.

## Features
- **Line Detection & Following**: Accurately detects and follows lane markings
- **Obstacle Detection**: Uses ultrasonic sensors to detect obstacles, sound an alert, and navigate around them
- **Traffic Sign Recognition**: Identifies STOP signs and responds appropriately by stopping the vehicle

## Hardware Components
- Raspberry Pi 3 Model B+
- Raspberry Pi Camera 5MP
- HC-SR04 Ultrasonic Sensor
- Motor controller
- Chassis and wheels

## Technologies Used
- **Image Processing**: OpenCV, NumPy
- **Camera Interface**: Picamera2
- **AI Model**: Cascade classifier for traffic sign recognition
- **Programming Language**: Python

## Algorithms
### Line Detection
- Image preprocessing using Gaussian blur
- HSV color space conversion and thresholding
- Perspective transformation for bird's-eye view
- Center point calculation for steering

### Traffic Sign Recognition
- Cascade classifier trained using OpenCV
- Custom dataset with labeled STOP signs
- Real-time detection during navigation

### Obstacle Avoidance
- Distance measurement using ultrasonic sensors
- Alert system (buzzer) when obstacles are detected
- Path adjustment algorithm for obstacle navigation

## Demo
[Demo.mp4]

## Team
Project developed as part of a research initiative at Ho Chi Minh City University of Technology and Education.

## Acknowledgements
Special thanks to Mr. Nguyen Xuan Sam for providing knowledge and support throughout the project development process. We also extend our gratitude to the authors of the research papers and studies we referenced.

## Contact
For more information, please contact [Your Contact Information].
