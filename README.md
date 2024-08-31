# Plant Image Classification

## Overview

This project utilizes TensorFlow and Keras to build and train a Convolutional Neural Network (CNN) for classifying plant images. The dataset used is sourced from Kaggle and consists of images categorized into different plant species. The project includes data preprocessing, model building, training, evaluation, and prediction.

## Key Results

- **Model Accuracy**: Achieved an impressive accuracy of **98.4%** on the test dataset.


## Project Structure

1. **Data Loading and Preprocessing**
   - Load images from the Kaggle dataset and preprocess them.
   - Split the dataset into training, validation, and test sets.

2. **Model Architecture**
   - Define a CNN with convolutional layers, pooling layers, and dense layers.
   - Include data augmentation and normalization.

3. **Training and Evaluation**
   - Compile and train the model.
   - Evaluate model performance on the test set.
   - Plot accuracy and loss graphs.

4. **Prediction**
   - Make predictions on test images.
   - Visualize the results with actual vs. predicted labels and confidence.

## Requirements

Ensure you have the following Python packages installed:

- `pandas`
- `tensorflow`
- `matplotlib`
