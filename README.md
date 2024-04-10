
Face Detection Application using OpenCV and Tkinter

This application utilizes OpenCV and Tkinter to implement real-time face detection through various techniques. Below is a breakdown of the key features and components of the application:

Features:

Face Detection Techniques:

Haar Cascade Classifier

Canny Edge Detection

Sobel Edge Detection

Kalman Filter

Hough Circle Transform

Convolutional Neural Network (CNN)

Camera Integration:

The application allows users to start the camera to perform real-time face detection.

Interactive UI:

Buttons are provided to toggle between different face detection techniques.

All-in-One Mode:

An option is available to enable an all-in-one mode where multiple face detection techniques are combined.

Components:

Main Script (main.py):

This script initializes the Tkinter GUI and defines functions for starting the camera, updating camera feed, and toggling different face detection techniques.

Face Detection Functions:

Each face detection technique is implemented as a separate function (detect_faces_*), where the selected technique is applied to the camera feed.

Global Variables:

Global variables are used to manage the state of different face detection techniques and the camera.

UI Elements:

Buttons are created for starting the camera, toggling different face detection techniques, and activating the all-in-one mode.

Background and Labels:

Background images and labels are added to enhance the visual appeal of the application.

Dependencies:

OpenCV:

Used for image processing, face detection, and video capture.

Tkinter:

Utilized for creating the graphical user interface.

Pillow (PIL):

Required for handling images in Tkinter.
