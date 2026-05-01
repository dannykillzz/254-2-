# 254-2-

Overview
This project combines computer vision and environmental sensing to create a smart, adaptive vision system. It performs real‑time human detection using a pre‑trained YOLO model and automatically adjusts screen or camera brightness based on ambient light levels. The goal is to improve visibility, reduce eye strain, and create a more responsive system that adapts to its surroundings.

Features

Human Detection (YOLO Pre‑Trained Model)
Uses a pre‑trained YOLO (You Only Look Once) model for fast and accurate human detection.
Automatic Brightness Adjustment
Reads ambient light levels using a light sensor or webcam‑based brightness estimation.
Dynamically adjusts screen or camera brightness.

How It Works

Human Detection Pipeline
Capture video frames from the camera.
Pass each frame through the YOLO model.
Identify humans based on YOLO’s object‑class predictions.
Display bounding boxes and confidence scores.
Brightness Adjustment Pipeline
Continuously measure ambient light.
Map light intensity to a brightness level.
Adjust display or camera brightness automatically.

Technologies Used
Python
OpenCV
YOLO Pre‑trained Model (YOLOv5 / YOLOv3 depending on implementation)
Laptop camera 

Project timeline 
Week 1 — Project Definition
During the first week, the team focused on defining the overall project idea, goals, and scope. We discussed what problem we wanted to solve and agreed on building a smart lightning system

Week 2 — Planning and System Architecture
In the second week, we shifted into planning and task distribution. Each team member was assigned responsibilities based on strengths and interests. We also designed the system architecture, outlining how the YOLO human‑detection module, the ambient‑light sensor, and the brightness‑adjustment logic would interact

Weeks 3–5 — Development and Implementation
Weeks three through five were dedicated to building and integrating the system:

Hardware Circuit Construction:  
We assembled the physical components, including the ambient‑light sensor and microcontroller setup.

Arduino Code Development:  
The team wrote and tested the Arduino code responsible for reading ambient‑light values and communicating with the Python system.

Python Implementation:  
We implemented the human‑detection pipeline using a pre‑trained YOLO model and connected it with the brightness‑adjustment module.

Weekly Progress Meetings
Throughout the project, the team held weekly progress meetings every Wednesday at the Milner Library. These meetings helped us stay aligned, review completed tasks, identify challenges, and plan the next steps

Contributors

MARCUS NGUYEN:

NOAH ADAMS:

DANIEL EDET:

KARIQ MEYERS:









