# Gesture Volume Control using OpenCV

A computer vision project that allows users to control the system volume using hand gestures. The application uses a webcam to detect hand landmarks in real-time and adjusts the system volume based on the distance between the thumb and index finger.

## Features

* Real-time hand tracking using MediaPipe
* System volume control through hand gestures
* Dynamic volume percentage display
* Interactive volume bar visualization
* FPS (Frames Per Second) monitoring
* Contact indication when fingers touch

## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy
* Pycaw
* Comtypes

## How It Works

1. The webcam captures live video frames.
2. MediaPipe detects hand landmarks.
3. The positions of the thumb tip and index finger tip are identified.
4. The distance between the two fingers is calculated.
5. The distance is mapped to the system volume range.
6. The system volume is updated in real time.
7. A volume bar and percentage are displayed on the screen.

## Hand Landmarks Used

* Thumb Tip → Landmark 4
* Index Finger Tip → Landmark 8

The distance between these landmarks controls the system volume.

## Installation

Clone the repository:

```bash
git clone <your-repository-link>
cd Gesture-Volume-Control
```

Install dependencies:

```bash
pip install opencv-python
pip install mediapipe
pip install numpy
pip install pycaw
pip install comtypes
```

## Run the Project

```bash
python vol_control.py
```

## Controls

* Move thumb and index finger closer → Decrease volume
* Move thumb and index finger apart → Increase volume
* Press `Q` to quit

## Project Structure

```text
Gesture-Volume-Control/
│
├── vol_control.py
├── HandTrackingModule.py
├── README.md
```

## Future Enhancements

* Brightness control using gestures
* Multi-hand gesture support
* Gesture-based media controls
* AI-based gesture recognition
* GUI dashboard for settings

## Learning Outcomes

This project helped in understanding:

* Computer Vision fundamentals
* Real-time image processing
* Hand landmark detection
* Human-computer interaction
* System-level volume control
* OpenCV and MediaPipe integration

## Author

Hanshitha Killi

Built as a Computer Vision project using OpenCV and MediaPipe.
