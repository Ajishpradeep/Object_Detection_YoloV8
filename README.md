# Object Detection Project

This project focuses on object detection using the YOLO (You Only Look Once) algorithm. It includes multiple chapters and projects that demonstrate various applications of object detection, such as car counting, people counting, PPE (Personal Protective Equipment) detection, and poker hand detection.

## Table of Contents

- [Overview](#overview)
- [Techniques Used](#techniques-used)
- [Chapter 5 - Running YOLO](#chapter-5---running-yolo)
- [Chapter 6 - YOLO with Webcam](#chapter-6---yolo-with-webcam)
- [Project 1 - Car Counter](#project-1---car-counter)
- [Project 2 - People Counter](#project-2---people-counter)
- [Project 3 - PPE Detection](#project-3---ppe-detection)
- [Project 4 - Poker Hand Detector](#project-4---poker-hand-detector)

## Overview

The Object Detection Project showcases the capabilities of the YOLO algorithm for object detection tasks. The projects included in this repository demonstrate different real-world applications of object detection, providing solutions for car counting, people counting, PPE detection, and poker hand detection. Each project includes the necessary code and resources to run and understand the implementations.

## Techniques Used

The following techniques are employed in the various projects:

- YOLO (You Only Look Once) Algorithm: The YOLO algorithm is used for real-time object detection. It divides the input image into a grid and predicts bounding boxes and class probabilities for each grid cell, enabling efficient and accurate object detection.

- Tracking: The projects involving counting people and cars utilize object tracking techniques to track the detected objects across frames, enabling accurate counting and analysis.

- Sort Algorithm: The `sort.py` script implements the SORT (Simple Online and Realtime Tracking) algorithm. It helps in tracking objects and associating detections across frames.

## Chapter 5 - Running YOLO

The chapter "Running YOLO" introduces the basics of running the YOLO object detection algorithm on images. It includes a Python script `Yolo-Basics.py` that demonstrates how to perform object detection on static images using YOLO.

## Chapter 6 - YOLO with Webcam

The chapter "YOLO with Webcam" showcases real-time object detection using the YOLO algorithm with a webcam. The Python script `Yolo-Webcam.py` captures video from the webcam and applies object detection using YOLO, providing a real-time detection experience.

## Project 1 - Car Counter

The "Car Counter" project focuses on counting cars in a video stream. The Python script `Car-Counter.py` utilizes the YOLO algorithm for object detection and incorporates tracking techniques to track and count cars accurately. It also includes the `graphics.png` and `mask.png` files used for visualization purposes.

## Project 2 - People Counter

The "People Counter" project aims to count the number of people in a video. The Python script `People-Counter.py` utilizes the YOLO algorithm for person detection and integrates object tracking for precise counting. The `graphics.png` and `mask.png` files are used for visualization purposes in the script.

## Project 3 - PPE Detection

The "PPE Detection" project focuses on detecting Personal Protective Equipment (PPE) in a video stream. The `ppe.pt` file contains pre-trained weights specific to PPE detection using YOLO. The Python script `PPEDetection.py` utilizes these weights to perform PPE detection in real-time.

## Project 4 - Poker Hand Detector

The "Poker Hand

 Detector" project involves detecting and analyzing poker hands using the YOLO algorithm. The `playingCards.pt` file contains pre-trained weights specific to playing card detection. The Python script `Poker-Hand-Detector.py` applies YOLO to detect cards in an image or video, and the `PokerHandFunction.py` script provides functions to analyze the detected cards and determine the poker hand.

## Instructions

Follow the instructions below to set up and run the projects:

1. Clone or download this project repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file using the following command:

   ```bash
   pip install -r requirements.txt
   ```

3. Navigate to the specific project directory you want to run.
4. Execute the corresponding Python script for the project using the following command:

   ```bash
   python <script_name>.py
   ```

   Replace `<script_name>` with the actual name of the Python script file.

   For example, to run the Car Counter project:

   ```bash
   cd Project_1_Car_Counter
   python Car-Counter.py
   ```

   Follow the same approach for other projects, ensuring that any required resources, such as image files or YOLO weight files, are placed in the appropriate directories as mentioned in the project descriptions.

Please note that the specific instructions and explanations for each project can be found in their respective directories.

Feel free to modify and adapt the code according to your specific needs. If you encounter any issues or have any questions, please don't hesitate to reach out for further assistance.
