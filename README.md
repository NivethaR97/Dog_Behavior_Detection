# 🐶 Dog Behavior Detection using Deep Learning
## 📌 Project Overview

This project is a real-time computer vision system designed to detect dog behavior (Normal or Aggressive) from video using deep learning techniques.

It uses object detection and image classification to analyze video frames and predict behavior in real time.

## 🚀 Features
- Real-time video processing     
- Dog detection using YOLOv8s (pretrained)  
- Behavior classification using EfficientNetB0 (Transfer Learning)  
- Frame-by-frame analysis using OpenCV    
- Binary classification: Normal vs Aggressive   
- ~90% accuracy
## 🧠 Tech Stack
- Python
- YOLOv8s (Pretrained COCO model)
- OpenCV
- EfficientNetB0 (Transfer Learning)
- Deep Learning
## ⚙️ System Workflow
- Video is processed frame by frame
- YOLOv8 detects dogs in each frame
- Detected dog region is cropped
- Cropped image is passed to EfficientNetB0
- Model predicts behavior:
  -  Normal
  -  Aggressive
## 📊 Dataset
- 1,400 images collected
- Folder-based structure:
 - Normal
 - Aggressive
- Binary classification task
## 📈 Performance
- Accuracy: ~90%
- Evaluation Metrics: Precision, Recall
## 📌 Key Learnings
- Working with pretrained YOLO models
- Image cropping and pipeline integration
- Video-based deep learning analysis
- Transfer learning using EfficientNetB0
## 🔮 Future Improvements
- Add object tracking for better temporal understanding
- Improve dataset diversity
- Enhance real-time performance optimization
## 🙏 Acknowledgements

Grateful to my mentors Ramisha Rani mam and Pooja mam for their guidance and support throughout this project.

## 🏷️ Tags

#DeepLearning #ComputerVision #YOLOv8 #EfficientNet #OpenCV #MachineLearning #AI
