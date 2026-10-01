# YOLOv8 Object Detection & Robustness Analysis

Evaluation of YOLOv8 object detection models on the COCO 2017
validation dataset, including robustness analysis under image distortions.

## Project Overview

The project evaluates object detection performance using:
- IoU
- Precision and Recall
- Average Precision (AP)
- mAP@50
- mAP@50-95

The robustness of YOLOv8 is also evaluated under:
- Gaussian noise
- Random occlusion
- JPEG compression

## Dataset

COCO 2017 Validation Set
- 5,000 images
- 80 object categories
- 36,781 annotated objects

## Models

- YOLOv8n
- YOLOv8s
- YOLOv8m
- YOLOv8l
- YOLOv8x

## Key Findings

- YOLOv8n achieved approximately 0.51 mAP@50 and 0.36 mAP@50-95
  on clean COCO validation images.
- Gaussian noise and JPEG compression caused substantial performance degradation.
- Random occlusion had a smaller overall effect.
- Detection performance varied significantly across object categories
  and object sizes.

## Technologies

Python, Ultralytics YOLOv8, COCO API, NumPy, OpenCV, Matplotlib
