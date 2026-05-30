# 🔵 Blue Color Detection using OpenCV

## Overview

This project uses OpenCV and Python to detect blue-colored objects in real-time through a webcam. The application identifies blue regions in the video feed, draws a bounding box around the detected object, and displays the label **"BLUE"** above it.

The project demonstrates fundamental computer vision concepts such as color segmentation, contour detection, image masking, and object tracking.

---

## Features

* Real-time webcam video processing
* Blue color detection using HSV color space
* Bounding box around detected blue objects
* Object labeling with color name
* Noise reduction using morphological operations
* Simple and lightweight implementation

---

## Technologies Used

* Python
* OpenCV
* NumPy

---

## How It Works

1. Captures video frames from the webcam.
2. Converts each frame from BGR to HSV color space.
3. Creates a mask for blue color pixels.
4. Applies erosion and dilation to reduce noise.
5. Detects contours from the mask.
6. Finds the largest blue regions.
7. Draws a rectangle around detected objects.
8. Displays the text **"BLUE"** above the object.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Hanshitha07/open_cv_projects.git
cd open_cv_projects
```

### Install Dependencies

```bash
pip install opencv-python numpy
```

---

## Running the Project

```bash
python color_detection.py
```

---

## Controls

| Key | Action               |
| --- | -------------------- |
| Q   | Quit the application |

---

## Project Structure

```text
open_cv_projects/
│
├── color_detection.py
├── README.md
```

---

## Concepts Learned

* Computer Vision Basics
* HSV Color Space
* Color Thresholding
* Contour Detection
* Morphological Operations
* Real-Time Video Processing

---

## Future Improvements

* Detect multiple colors simultaneously
* Display color percentage confidence
* Track object movement
* Color-based object counting
* Integration with robotics applications

---

## Author

**Hanshitha Killi**

Built as part of my Computer Vision and OpenCV learning journey.
