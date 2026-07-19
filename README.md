# Multi-Object Detection & Tracking for Drones

This project is based on **Multi-Object Detection and Tracking for drone videos** using **YOLO26n** and **ByteTrack**. The main goal of this project is to detect and track multiple objects such as humans and vehicles from aerial/drone footage.

The system uses **YOLO26n** for object detection and **ByteTrack** for tracking objects across video frames. Each detected object is assigned a unique and persistent ID, which helps to track the movement of the same object throughout the video.

## Dataset

**Detection Dataset:** VisDrone2019-DET  
**Tracking Dataset:** VisDrone2019-MOT  

## Detection Model

**YOLO26n**

## Tracking Algorithm

**ByteTrack**

## Classes

- Pedestrian
- Person
- Car
- Van
- Truck
- Bus

## Training Details

**Epochs:** 100  
**Batch Size:** 16  
**Image Size:** 640  

## Performance

**mAP50:** 42%  
**mAP50-95:** 25%  

## Features

✓ Drone-based object detection  
✓ Multi-object tracking  
✓ Persistent object IDs  
✓ Vehicle tracking  
✓ Human tracking  
✓ Detects small objects in aerial views  
✓ Works on drone video footage  
✓ Useful for surveillance and traffic monitoring  

## Applications

- Drone surveillance
- Traffic monitoring
- Crowd analysis
- Smart city monitoring
- Vehicle counting
- Human movement tracking
- Road safety analysis

## Project Summary

This project provides a simple and effective approach for detecting and tracking multiple objects in drone videos. By combining **YOLO26n** with **ByteTrack**, the system can detect objects in each frame and maintain their identity across the video. It is useful for real-world aerial monitoring tasks where both detection accuracy and object tracking are important.
