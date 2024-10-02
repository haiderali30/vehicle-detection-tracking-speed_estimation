# Vehicle Speed Estimation and Collision Detection
This project is a Python-based application that utilizes the YOLOv8 model to detect and track vehicles in a video, estimate their speed, and detect potential collisions between them. The project leverages OpenCV for video processing and uses pre-trained models for object detection and tracking.

# Features
Vehicle Detection: Uses YOLOv8 to detect vehicles in video frames.
Speed Estimation: Estimates the speed of each detected vehicle using bounding boxes and pre-defined lines on the road.
Collision Detection: Identifies potential collisions between vehicles based on their proximity and bounding box overlap (IoU).
Video Processing: Processes input video frames and writes the output with bounding boxes, vehicle speeds, and collision alerts.

# Installation
Clone the repository:
git clone https://github.com/yourusername/vehicle-speed-estimation.git

Install the required dependencies

Ensure that you have the following installed:
opencv-python
ultralytics (for YOLOv8)
numpy
math

Download the YOLOv8 model:
The script uses YOLOv8 for vehicle detection. You can download the model weights using the provided script or directly from Ultralytics YOLOv8.
