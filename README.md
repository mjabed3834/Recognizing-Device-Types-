# Image Classification: BP Monitor vs. Glucose Meter

## Description:
This project involves classifying images of medical devices into two categories: **Blood Pressure (BP) Monitors** and **Glucose Meters**. The model is based on the **EfficientNet** architecture and has achieved **96% accuracy** in classifying images into the appropriate categories. The dataset includes images of both BP monitors and glucose meters, and EfficientNet is used to achieve high classification accuracy with fewer parameters compared to traditional models.

### Key Features:
- EfficientNet-based image classification model.
- Classifies images into two categories: BP Monitor and Glucose Meter.
- Achieved **96% accuracy**.
- Utilizes a dataset with labeled images of BP monitors and glucose meters for training and testing.
- Supports both training and inference tasks.

## Requirements:
- `tensorflow` for model training and inference.
- `numpy`, `matplotlib`, and `PIL` for image processing and visualization.
- `efficientnet` Python package for the EfficientNet model.

## Installation:
1. Install required libraries:
   ```bash
   pip install tensorflow numpy matplotlib pillow efficientnet
