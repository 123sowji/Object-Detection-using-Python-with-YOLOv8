Overview

This project offers a graphical user interface (GUI) for real-time object detection using the YOLOv8 model. Users can:

Upload images from their local system for object detection.

Utilize their webcam for real-time object detection.


The application leverages the YOLOv8 model from the Ultralytics library, ensuring state-of-the-art performance in object detection tasks.

Features

Image Upload: Select and process images from your local storage to detect objects.

Webcam Integration: Activate your webcam to perform real-time object detection.

Bounding Boxes: Visualize detected objects with bounding boxes, labels, and confidence scores.


Installation

Prerequisites

Ensure you have the following installed:

Python 3.8 or higher

pip (Python package installer)



Using the Application

Upload Image:

Click the "Upload Image" button.

Select an image file from your local system.

The application will display the image with detected objects highlighted.


Start Webcam:

Click the "Start Webcam" button.

A new window will display the webcam feed with real-time object detection.

Press the 'ctrl+c' key to exit the webcam feed.


Acknowledgements

Ultralytics: For the YOLOv8 model and related resources.

OpenCV: For real-time computer vision capabilities.

Tkinter: For the GUI components.