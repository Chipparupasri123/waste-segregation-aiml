# AI-Based Waste Segregation System

This project implements a Deep Learning-based image classification system using MobileNetV2 to classify waste into Dry and Wet categories.

## Model Information
The model was trained locally using categorized waste images.
The trained model file (waste_segregation_model.h5) is included in this repository.

## Dataset
Only sample images are included here for demonstration.
The full dataset was used during training but is not uploaded to reduce repository size.

## How It Works
1. Load the saved model.
2. Provide a new waste image.
3. The system predicts whether the waste is Dry or Wet.

## Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2
- Jupyter Notebook
## Trained Model File

The file `waste_segregation_model.h5` contains the fully trained deep learning model.

This file stores:
- Model architecture
- Learned weights
- Training configuration

The saved model allows predictions to be made without retraining the model again.
To use it, the model can be loaded in Python using TensorFlow.
