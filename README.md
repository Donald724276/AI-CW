# Deepfake Detection using ResNet50
### COMP-1828 Intro to AI Coursework.

This repository contains a deep learning model for detecting deepfake images using transfer learning with ResNet50 architecture.

## Overview
The model is trained on the "140k Real and Fake Faces" dataset from Kaggle and uses a pre-trained ResNet50 model with custom classification layers to distinguish between real and AI-generated faces.

## Dataset
- Source: 140k Real and Fake Faces
- Structure: The dataset is organized into train, validation, and test folders with binary classification (Real vs Fake)

## Requirements
The notebook is designed to run on Google Colab with GPU acceleration. Required libraries:

- TensorFlow/Keras
- Kaggle API
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage Instructions
To use the pre-trained model weights for inference:
1. Run Cell 1: Download and prepare the dataset
2. Run Cell 2: Set up data generators
3. Run Cell 3: Build the model architecture
4. Run Cell 8: Upload the weights.keras weights file when prompted
5. Run Cell 6.1: Generate accuracy and loss graphs
6. Run Cell 6.2: Visualize predictions on sample images
7. Run Cell 7: Display confusion matrix.
