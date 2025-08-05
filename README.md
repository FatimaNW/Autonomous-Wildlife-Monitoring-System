# 🖥 Autonomous Wildlife Monitoring System

The **Autonomous Wildlife Monitoring System** is designed to detect, track, and analyze wildlife through video and sound detection. This system leverages AI techniques like Computer ision and Audio Processing, making it ideal for wildlife research, conservation efforts, and security purposes.

## 🛠 Technologies Used  
- **Computer Vision**: OpenCV, Haar Cascade, YOLOv8  
- **Audio Processing**: Librosa  
- **Visualization**: Matplotlib  
- **Programming Language**: Python

## 🚀 Features  

### 1. Image Detection  

Image detection in this system utilizes YOLOv8 to detect animals in images, drawing bounding boxes with labels and confidence scores. It employs Dijkstra's Algorithm to analyze the spatial relationships between animals, measuring the distances between them. These interactions are then visualized using Matplotlib, providing insights into animal positions, movements, and behaviors.

![Zebra Output](https://github.com/FatimaNW/Autonomous-Wildlife-Monitoring-System/blob/main/Output%20Files/zebra2_output.png)


<img src="https://github.com/FatimaNW/Autonomous-Wildlife-Monitoring-System/blob/main/Output%20Files/zebra2_animal_graph.png" alt="Zebra Graph" width="650" height="600">

### 2. Sound Detection 

Sound Detection analyzes and classifies animal sounds using Librosa with audio normalization and visualization. Emotion-based color coding and a an animal mood classifier detects the emotional states of animals, providing insights into animal behavior.

<img src="https://github.com/FatimaNW/Autonomous-Wildlife-Monitoring-System/blob/main/Output%20Files/sound_output.png" alt="Sound Graph" width="650" height="600">

### 3. Video Detection    

Identifies animals like in video frames using Haar Cascade and YOLO. OpenCV processes frames, draws bounding boxes, and displays confidence scores. Google Colab Patches enable frame display within Jupyter notebooks.

<img src="https://github.com/FatimaNW/Autonomous-Wildlife-Monitoring-System/blob/main/Output%20Files/output_videoFrame2.PNG" alt="Video Frame 1" width="650" height="600">
<img src="https://github.com/FatimaNW/Autonomous-Wildlife-Monitoring-System/blob/main/Output%20Files/output_videoFrame3.PNG" alt="Video Frame 2" width="650" height="600">

## 🧭 How to Use

1. Download the `.ipynb` files from this repository.
2. Open them in Google Colab or Jupyter Notebook.
3. Upload the `input/` folder (containing the sample images, videos, and audio files) into your Colab/Jupyter environment.
4. Update the file paths in the notebooks to point to the files inside your uploaded `input/` folder.
5. Run the notebook cells:
   - **Image and audio detections**: Results (labels, distances, mood) will be displayed directly in the output terminal, not saved as files.
   - **Video detection**: Processed frames will be shown in the terminal, and a separate output video file (with detections drawn) will be generated.

