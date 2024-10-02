# Vehicle Speed Estimation and Collision Detection
This project is a Python-based application that utilizes the YOLOv8 model to detect and track vehicles in a video, estimate their speed, and detect potential collisions between them. The project leverages OpenCV for video processing and uses pre-trained models for object detection and tracking.

Features
Vehicle Detection: Uses YOLOv8 to detect vehicles in video frames.
Speed Estimation: Estimates the speed of each detected vehicle using bounding boxes and pre-defined lines on the road.
Collision Detection: Identifies potential collisions between vehicles based on their proximity and bounding box overlap (IoU).
Video Processing: Processes input video frames and writes the output with bounding boxes, vehicle speeds, and collision alerts.

