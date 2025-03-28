# Car Park Management System

This project is a car park management system that uses computer vision to monitor parking spaces.

## Features

- Detects and highlights parking spaces in a given image or video.
- Counts the number of free spaces.
- Allows manual adjustment of parking space locations via mouse clicks.

## Dependencies

- OpenCV (cv2)
- Pickle
- cvzone
- numpy

## Installation

1. Install the required Python packages if you haven't already:
   pip install opencv-python-headless pickle5 cvzone numpy

```bash
pip install opencv-python-headless pickle5 cvzone numpy

Clone this repository or download the scripts.
Usage
Run the first script to define the parking spaces. Left-click to mark the top-left corner of a space, and right-click to remove a space.
Run the second script to start monitoring the parking spaces in a video. The number of free spaces will be displayed on the video.


