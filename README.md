# Face-Recognition-with-OpenCV-and-dlib

## Overview

This project implements real-time face recognition using OpenCV and dlib's face_recognition library. It captures video from a webcam, detects faces, and matches them against a known face encoding. If a match is found, the person's name is displayed; otherwise, the face is labeled as "Unknown."

## Requirements

Before running the code, ensure you have the following dependencies installed:

- Python 3.12 (or compatible version)
- OpenCV (opencv-python)
- NumPy (numpy)
- dlib (Precompiled .whl file for Windows)
- face-recognition (face_recognition library)
- Matplotlib (matplotlib)

## Installation

Install OpenCV:
pip install opencv-python

Install NumPy:
pip install numpy

Install face-recognition:
pip install face-recognition

Install Matplotlib:
pip install matplotlib

## Running the Project

1. Ensure your webcam is connected and accessible.

2. Run the script:

python face_recognition.ipynb

The program will capture video, detect faces, and attempt to recognize them.

Press q to exit the application.

## How It Works

-The program loads an image of a known person and encodes the facial features.

- It captures video frames from the webcam and converts them to RGB format.

- It detects faces in the frame and compares them against the known encoding.

- If a match is found, it displays the corresponding name; otherwise, it labels the face as "Unknown."

- A rectangle is drawn around detected faces along with the name (if recognized).

## Troubleshooting

- If you face issues installing dlib, ensure you are using the correct .whl file for your Python version.

- Ensure the webcam is properly connected and accessible.

- If the face is not detected, try using a clearer reference image with better lighting.
