# Autonomous Wildlife Monitoring System

The **Autonomous Wildlife Monitoring System** is designed to detect, track, and analyze wildlife through video and sound detection. This system leverages AI techniques like Computer ision and Audio Processing, making it ideal for wildlife research, conservation efforts, and security purposes.

## Technologies Used  
- **Computer Vision**: OpenCV, Haar Cascade, YOLOv8  
- **Audio Processing**: Librosa  
- **Visualization**: Matplotlib  
- **Programming Language**: Python

## Features  

### 1. Image Detection  

Image detection in this system utilizes YOLOv8 to detect animals in images, drawing bounding boxes with labels and confidence scores. It employs Dijkstra's Algorithm to analyze the spatial relationships between animals, measuring the distances between them. These interactions are then visualized using Matplotlib, providing insights into animal positions, movements, and behaviors.

### 2. Sound Detection 

Sound Detection analyzes and classifies animal sounds using Librosa with audio normalization and visualization. Emotion-based color coding and a an animal mood classifier detects the emotional states of animals, providing insights into animal behavior.

### 3. Video Detection    

Identifies animals like in video frames using Haar Cascade and YOLO. OpenCV processes frames, draws bounding boxes, and displays confidence scores. Google Colab Patches enable frame display within Jupyter notebooks.
