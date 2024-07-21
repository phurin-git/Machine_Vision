# Machine Vision Project with Python and OpenCV

This repository features a machine vision project using Python and OpenCV to detect various geometric shapes, including circles, triangles, rectangles, and pentagons. The project provides a graphical user interface (GUI) with three tabs to facilitate real-time object detection, camera calibration, and filter parameter adjustment.

## Features

- Object Detection: Detects and identifies geometric shapes (circles, triangles, rectangles, pentagons) in real-time using OpenCV filters.
- GUI Interface: Includes a user-friendly GUI with three tabs for different functionalities:
    - Measurement Tab: Displays real-time object detection results and visualizes the identified shapes.
    - Calibration Tab: Provides tools for calibrating the camera using a checkerboard pattern to improve accuracy.
    - Parameter Tab: Allows users to set and adjust filter thresholds to optimize detection performance.


## Components

- Python: The programming language used for developing the project.
    - OpenCV (cv2): Essential for computer vision tasks, including real-time object detection and image processing.
    - Pillow (PIL): Used for image handling and integration with the Tkinter GUI.
    - NumPy: Provides support for numerical operations on images and arrays.
    - Imutils: Offers convenience functions for image processing, such as resizing and displaying images.
    - Tkinter: The standard Python library for creating the graphical user interface (GUI) of the application.
    - Math: Provides mathematical functions used for geometric calculations related to shape detection.
    - Glob: Used for file handling, particularly for searching for calibration images.
    - Time: Handles time-related functions, useful for timing operations and delays.
- USB Camera: Captures real-time video feed for object detection and calibration.