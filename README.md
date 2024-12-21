# Hand Gesture Volume Control

This Python project uses computer vision and hand gesture recognition to control the system volume. By recognizing the positions of the index finger and thumb, the program increases or decreases the system volume accordingly.

## Features
- Recognizes hand gestures in real-time via a webcam.
- Adjusts the system volume:
  - **Pointing up gesture**: Increases the volume.
  - **Pointing down gesture**: Decreases the volume.

## Technologies Used
- **OpenCV**: For capturing video from the webcam and processing the image frames.
- **Mediapipe**: For detecting and tracking hand landmarks.
- **PyAutoGUI**: For simulating keyboard key presses to control system volume.

## Requirements
Make sure you have Python 3.x installed, along with the required dependencies:

- `opencv-python`
- `mediapipe`
- `pyautogui`

You can install the required libraries using:
```bash
pip install opencv-python mediapipe pyautogui
