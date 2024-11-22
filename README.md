# Human-Activity-Recognition-using-Multiclass-Classification-

This project involves classifying human activities (e.g., walking, sitting, standing) based on data collected from the accelerometer and gyroscope sensors of a smartwatch. The data was collected from 30 participants performing six predefined activities in a controlled environment. Using multiclass classification techniques, the project predicts the activity type from sensor readings.

## Dataset
**Name**: UCI HAR Dataset
**Source**: University of California, Irvine (UCI) Machine Learning Repository.
**Description**:
Data collected from the accelerometer and gyroscope sensors of a smartphone worn by participants.
**Sampling rate**: 50Hz.
**Features**: 561 attributes derived from 3-axial linear acceleration and angular velocity.
**Classes**: 
    **Six activities**:
    - Laying
    - Walking
    - Sitting
    - Standing
    - Climbing Up
    - Climbing Down

## Model Used
The project uses the Random Forest Classifier as the primary algorithm due to its:
- High accuracy for multiclass classification tasks.
- Ability to handle noisy and high-dimensional data.

## Features
The dataset contains pre-processed features, including:
**Time domain features**: Mean, standard deviation, etc.
**Frequency domain features**: Fast Fourier Transform (FFT) features.
**Body acceleration** and **gravity acceleration** components.
**Jerk signals** and **angular velocity** metrics.

## Evaluation Metrics
**Accuracy**: Measures overall prediction correctness.
**Precision, Recall, F1-Score**: Evaluates per-class performance.
**Confusion Matrix**: Visualizes misclassification rates for each class.

## Conclusion
The Random Forest Classifier achieves an accuracy of over 92%, effectively identifying human activities based on smartwatch sensor data. The confusion matrix and classification report indicate a strong model performance, with minimal misclassifications. This project highlights the potential of machine learning in activity recognition tasks, paving the way for applications in fitness tracking, health monitoring and human-computer interaction.
