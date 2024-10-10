# Smoking Detection System Using YOLOv5
![image](https://github.com/user-attachments/assets/ca249ea9-9082-4cf9-b4df-332247cc3c99) ![image](https://github.com/user-attachments/assets/6c38fbf8-48bd-4517-b9cd-5d4d64c09825)


This project implements a smoking and vaping detection system using the YOLOv5 object detection model. The system identifies instances of smoking or vaping in images, videos, or live camera feeds and triggers an alert upon detection.

## Installation and Setup

1. Create a Conda Environment

conda create -n smoke_detect python=3.9

conda activate smoke_detect

2. Install PyTorch for CPU

pip install torch==2.3.0 torchvision torchaudio --index-url https://download.pytorch.org/whl/test/cpu

3. Clone the YOLOv5 Repository

git clone https://github.com/ultralytics/yolov5

cd yolov5

4. Install YOLOv5 Requirements

pip install -r requirements.txt

## Running the Model

## Load the YOLOv5 model: 

Use the pre-trained YOLOv5 model from Ultralytics or load your custom-trained model.
## Test with images/videos: 

Detect smoking or vaping from images, videos, or live camera feeds.

## Features

- Real-time smoking detection via webcam
- Detects smoking/vaping from images and video files
- Alert system for smoking detection
