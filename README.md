# Handwritten Character Recognition
Machine Learning Internship – CodeAlpha

## Overview
This project implements a Handwritten Character Recognition system using a
Convolutional Neural Network (CNN). The model is trained to recognize handwritten
digits from image data.

## Dataset
- Name: MNIST Handwritten Digits Dataset
- Image Size: 28 × 28 (Grayscale)
- Classes: Digits (0–9)

## Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- VS Code

## Project Workflow
1. Loaded the MNIST dataset
2. Normalized pixel values and reshaped images for CNN input
3. Applied one-hot encoding to target labels
4. Built a CNN model using Conv2D, MaxPooling, Dense, and Dropout layers
5. Trained the model on training data
6. Evaluated the model on test data

## Model Details
- Model Type: Convolutional Neural Network (CNN)
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy

## Evaluation & Visualization
- Training vs Validation Accuracy graph
- Training vs Validation Loss graph
- Sample prediction visualization on test images

## Results
The CNN model achieved high accuracy on the test dataset and successfully
classified handwritten digits.

## Conclusion
This project demonstrates the use of deep learning and CNNs for image
classification tasks and provides practical experience in computer vision.

## Author
Deepak Vikal  
Machine Learning Intern – CodeAlpha
