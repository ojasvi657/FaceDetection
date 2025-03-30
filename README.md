# FaceDetection
# Real-time Face Detection Using OpenCV

This repository contains a simple implementation of real-time face detection using OpenCV's Haar Cascade Classifier. The application captures video from a webcam and detects faces in the live feed, drawing rectangles around detected faces.

## Requirements

To run this program, you need to have the following installed:

- **Python 3.x**
- **OpenCV for Python**

## How It Works
The program captures video from your webcam using OpenCV's VideoCapture method.
It converts each frame to grayscale to simplify the detection process.
The detectMultiScale method is used to detect faces in each frame:
scaleFactor: Specifies how much the image size is reduced at each image scale.
minNeighbors: Specifies how many neighbors each candidate rectangle should have to retain it.
minSize: Minimum possible object size.
Detected faces are outlined with rectangles.
Press the "a" key to exit the application.

## Overview

<img width="953" alt="image" src="https://github.com/user-attachments/assets/69e149d2-c9d9-4d03-ab37-1aa778f607bf" />

