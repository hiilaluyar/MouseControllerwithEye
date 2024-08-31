# Eye-Controlled Mouse Using OpenCV, MediaPipe, and PyAutoGUI

This project allows you to control your mouse cursor using your eye movements detected through a webcam. The project uses Python libraries such as OpenCV for video capture, MediaPipe for facial landmark detection, and PyAutoGUI for controlling the mouse.

## Features

- **Face Mesh Detection:** Uses MediaPipe to detect facial landmarks, focusing on eye movements.
- **Real-Time Mouse Control:** The mouse cursor is controlled in real-time based on the position of specific eye landmarks.
- **Eye Blink Click:** Blinking your eyes triggers a mouse click event.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install the required Python packages:
    ```bash
    pip install opencv-python mediapipe pyautogui
    ```

## Usage
1. Run the Python script:
    ```bash
    python eye_mouse_control.py
    ```
2. The script will start capturing video from your webcam. Position yourself in front of the camera.

3. Move your eyes to control the mouse pointer. Blinking will trigger a mouse click.

## Acknowledgments

- [MediaPipe](https://github.com/google/mediapipe)
- [OpenCV](https://opencv.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)
