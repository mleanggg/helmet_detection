# Helmet Detection using Faster R-CNN

## Project Overview
This project is an AI-based object detection system that detects whether a person is wearing a helmet or not in images.  
It is designed for safety monitoring in construction sites and road surveillance systems.

The model is trained using **Faster R-CNN with a ResNet-50 backbone**.

## Model Architecture
- Model: Faster R-CNN
- Backbone: ResNet50 + FPN
- Framework: PyTorch + TorchVision
- Task: Object Detection (Bounding Box + Classification)

## Dataset
- Source: Kaggle (Helmet Detection Dataset)
- Classes:
  - helmet
  - no_helmet

Dataset link:
https://www.kaggle.com/datasets/andrewmvd/helmet-detection

## Features
- Data augmentation (flip, scale, color jitter)
- Class imbalance handling (weighted loss + weighted sampler)
- IoU-based evaluation
- Mean Average Precision (mAP)
- Confusion Matrix analysis
- Early stopping to prevent overfitting
- Visualization of predictions

## Evaluation Metrics
- Precision
- Recall
- F1 Score
- IoU (Intersection over Union)
- mAP@0.5 / mAP@0.75 / mAP@0.5:0.95

## Results
- Model achieves strong detection performance on validation and test sets
- Outputs bounding boxes for:
  - helmet (green)
  - no_helmet (red)
    
## Google Drive (Model Weights)

The trained model weights are stored in Google Drive due to GitHub file size limitations.

### Model Weights
- 🔗 https://drive.google.com/drive/folders/1MKlCOxn3KonWuqMXCn602Z5Kr9AUcsPv
