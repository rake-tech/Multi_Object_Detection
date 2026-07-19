Multi-Object Detection & Tracking for Drones
This project is a drone-based object detection and tracking system built using YOLO26n and ByteTrack. It detects and tracks multiple objects from aerial videos, including humans and vehicles, and assigns each object a unique ID so it can be followed across frames.
The system is trained on the VisDrone2019 dataset, which is specially designed for drone-view object detection and tracking. Since drone footage often contains small objects, crowded scenes, different camera angles, and moving backgrounds, this project focuses on improving detection and tracking in real-world aerial environments.
Project Overview
Detection Model: YOLO26n
Tracking Algorithm: ByteTrack
Dataset: VisDrone2019-DET and VisDrone2019-MOT
Object Classes: Pedestrian, Person, Car, Van, Truck, Bus
Epochs: 100
Batch Size: 16
Image Size: 640
Performance
The trained model achieved the following results:
Metric	Result
mAP50	42%
mAP50-95	25%

Key Features
Detects multiple objects in drone videos
Tracks people and vehicles across frames
Assigns persistent IDs to each detected object
Works with aerial/drone-view datasets
Supports human and vehicle tracking
Useful for traffic monitoring, surveillance, and crowd analysis
Lightweight YOLO26n model for faster detection
ByteTrack integration for smooth multi-object tracking
Why This Project?
Drone videos are difficult to analyze because objects often appear small, overlap with each other, or move quickly across the frame. This project combines YOLO26n for fast object detection and ByteTrack for reliable tracking, making it easier to monitor people and vehicles from aerial footage.
Applications
Drone surveillance
Traffic monitoring
Smart city systems
Crowd movement analysis
Road safety monitoring
Vehicle counting
Human activity tracking
Emergency and rescue operations
