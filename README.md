O9# Tennis Analysis

## Introduction
This project provides an in-depth analysis of tennis gameplay by detecting and tracking players and the tennis ball in video footage. It measures player speed, ball shot speed, and the number of shots during a match. The system utilizes YOLO for object detection and CNNs for court keypoint extraction, ensuring accurate analysis and visualization.

## Output Videos
Below is a screenshot from one of the generated output videos showcasing the analysis process:

![Screenshot](output_videos/screenshot.jpeg)

## Models Used
This project leverages the following pre-trained and fine-tuned models:

- **YOLO v8:** For player detection.  
- **Fine-Tuned YOLO:** For tennis ball detection.  
- **CNNs for Court Keypoint Extraction:** Used to extract tennis court keypoints.  

### Pre-trained Models:
- [Trained YOLOv5 model for tennis ball detection](https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing)  
- [Trained model for tennis court keypoint extraction](https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing)  

## Training
To train the models used in this project, refer to the following notebooks:  

- **Tennis Ball Detector with YOLO:** [`training/tennis_ball_detector_training.ipynb`](training/tennis_ball_detector_training.ipynb)  
- **Tennis Court Keypoint Detection with PyTorch:** [`training/tennis_court_keypoints_training.ipynb`](training/tennis_court_keypoints_training.ipynb)  

## Requirements
Ensure the following dependencies are installed before running the project:  

- Python 3.8  
- ultralytics  
- pytorch  
- pandas  
- numpy  
- opencv-python  
