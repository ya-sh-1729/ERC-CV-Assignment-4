# ERC-CV-Assignment-4-Question-1



## Problem Statement

Write a Python program using MediaPipe to detect and draw hand contours on a live webcam feed. The program should:

Use a live feed from the webcam to continuously detect hands.
Draw the detected hand landmarks and connections (contours) on the video frame in real-time.
Flip the frame horizontally for a mirror effect.
Stop the video feed when the user presses the 'q' key.


## Working behind Hand Detection:

### MediaPipe
MediaPipe is an open-source Python library developed by Google that provides a comprehensive suite of tools for building applications that process and analyze multimedia data, such as images and videos. It offers a wide range of pre-built machine learning models and pipelines for tasks like facial recognition, hand tracking, pose estimation, object detection, and more. MediaPipe simplifies the development of computer vision, making it accessible to developers with various levels of expertise. It is often used in applications related to augmented reality, gesture recognition, and real-time tracking, among others.

### Hand Landmarks in MediaPipe
In MediaPipe, hand landmarks refer to the precise points or landmarks detected on a human hand in an image or video. The library's Hand module provides a machine learning model that can estimate the 21 key landmarks on a hand, including the tips of each finger, the base of the palm, and various points on the fingers and hand. These landmarks can be used for various applications, such as hand tracking, gesture recognition, sign language interpretation, and virtual reality interactions. MediaPipe's hand landmarks model makes it easier for developers to create applications that can understand and respond to hand movements and gestures in real-time.

### Reference material
https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker
https://pypi.org/project/mediapipe/
