# Face Detection Application

Welcome to the Face Detection Application, a real-time face detection system using OpenCV and Tkinter. This application demonstrates the power of computer vision with an interactive and user-friendly interface.

# Key features:

- Multiple detection modes:

  - Haar + Canny and Haar + Sobel edge overlays
  
  - Haar cascade face tracking with a Kalman filter prediction
  
  - Haar + Hough circle detection inside detected face regions
  
  - A pre-trained CNN (OpenCV’s SSD model) for more robust face bounding boxes
  
  - An “all-in-one” mode that runs Haar, CNN and Kalman in combination

- Interactive controls:

  - “Start Camera” button to begin the live feed
  
  - Toggle buttons (CED, SED, KFR, HTR, CNN, AAM) to switch between detection algorithms
  
  - Dynamic display of bounding boxes, edge overlays and predicted face centers

Under the hood it uses OpenCV’s DNN module for the CNN detector, cv2.CascadeClassifier for Haar cascades, NumPy for data handling, and PIL/ImageTk to render frames in the Tkinter window.

## Features

- **Multiple Detection Techniques**: Includes Haar Cascade, Canny and Sobel Edge Detection, Kalman Filter, Hough Circle Transform, and CNN.
- **Camera Integration**: Real-time face detection with live camera feed.
- **Interactive UI**: Toggle between detection techniques with ease.
- **All-in-One Mode**: Combine multiple techniques for robust detection.

## Components

- **Main Script (Face_Detection.ipynb)**: Initializes the GUI and orchestrates the application flow.
- **Face Detection Functions**: Separate functions for each detection technique, applied to the camera feed.
- **Global Variables**: Manage the state of detection techniques and camera.
- **UI Elements**: Interactive buttons and visual cues for a seamless experience.
- **Background and Labels**: Aesthetic elements to enhance user engagement.

## Dependencies

- **OpenCV**: The backbone for image processing and face detection.
- **Tkinter**: For crafting the graphical user interface.
- **Pillow (PIL)**: Image handling within the Tkinter environment.

## Getting Started

To get started with the Face Detection Application, clone the repository and install the required dependencies. Run `Face_Detection.ipynb` to launch the application.

## Contribution

We welcome contributions! If you have suggestions or want to add new features, please feel free to fork the repository and submit a pull request.

Embark on the journey of computer vision with our Face Detection Application. Your gateway to exploring the fascinating world of face detection awaits!
