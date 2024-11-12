# Banknote Classification Model using Xception CNN Architecture

An advanced computer vision system built with TensorFlow and Xception architecture to distinguish between genuine and counterfeit banknotes through analysis of security features.

## Project Overview

This system leverages deep learning to analyze specific regions of interest (ROIs) in banknote images, focusing on security features such as:
- Optical Variable Devices (OVD)
- Concealed Values
- Other security elements

The model achieves this through a combination of image preprocessing, feature extraction, and deep learning classification using the Xception architecture.

## Features

- **Image Preprocessing Pipeline**
  - Automated ROI extraction
  - Image resizing and standardization
  - Edge detection
  - Normalization

- **Deep Learning Classification**
  - Transfer learning using Xception architecture
  - Binary classification (Genuine/Counterfeit)
  - Batch normalization for improved training
  - Dropout layers for preventing overfitting

- **Evaluation Metrics**
  - Confusion matrix visualization
  - Accuracy, Precision, Recall, and F1-Score metrics
  - Prediction probability distribution analysis
  - Training/Validation performance curves

## Technical Stack

- **Framework**: TensorFlow/Keras
- **Base Model**: Xception (pretrained on ImageNet)
- **Image Processing**: OpenCV, Pillow
- **Data Analysis**: NumPy, Matplotlib, Scikit-learn
- **Development Environment**: Google Colab

## Prerequisites

```python
# Required Python packages
tensorflow>=2.0.0
opencv-python>=4.5.0
pillow>=8.0.0
numpy>=1.19.0
matplotlib>=3.3.0
scikit-learn>=0.24.0
```
