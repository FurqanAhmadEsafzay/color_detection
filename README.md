# 🎨 Real-Time Color Detection using OpenCV

This project demonstrates how to detect and track specific colors in real-time using OpenCV and Python. It leverages the HSV color space to isolate a target color (like red or black) from a webcam feed, draws bounding boxes around detected regions, and displays the live output.

---

## 📷 Project Overview

Color detection is a common computer vision task with applications in robotics, human-computer interaction, industrial inspection, and more. In this project:

- A webcam captures real-time video frames.
- Frames are converted to the HSV color space.
- A color mask is applied to detect specific colors.
- Contours of the detected color regions are extracted.
- Bounding boxes are drawn around the detected objects.

You can switch between detecting **red**, **yellow**, **black**, or any custom color by updating HSV range thresholds in the code.

---

## 🛠️ Technologies Used

- 🐍 Python
- 📦 OpenCV (`cv2`)
- 📷 Webcam for real-time input
- 💡 NumPy

---

## 🧪 How It Works

1. Convert BGR to HSV for better color range separation.
2. Apply a mask using defined HSV thresholds for the target color.
3. Use contour detection to find the colored regions.
4. Filter small areas to ignore noise.
5. Draw bounding rectangles on valid detections.

---

## 🚀 Getting Started

### Prerequisites

Install dependencies:

```bash
pip install opencv-python numpy
