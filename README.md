# Facial Recognition and Gender Bias Analysis

## Project Overview

This project investigates the potential gender biases in facial recognition technology. While advancements in facial recognition algorithms, such as FaceNet, have improved accuracy with features like facial landmarks and Local Binary Patterns, concerns persist regarding their performance across different genders. This study focuses on analyzing the relationship between facial recognition accuracy and gender biases, particularly in sensitive applications like law enforcement and surveillance.

## Objectives

1. **Performance Comparison**: Evaluate the performance of the FaceNet algorithm on male and female subjects.
2. **Gender Prediction**: Use FaceNet embeddings to predict the gender of individuals and assess the effectiveness compared to other methods.

## Analyses

### 1. FaceNet Performance Comparison

- **Dataset**: Labeled Faces in the Wild (LFW) dataset.
- **Method**: Split the dataset by gender and apply an L2-distance threshold to distinguish between facial embeddings. Transform the recognition task into a classification problem.
- **Metrics**: Accuracy, precision, recall, and F1 score.

### 2. Gender Prediction Using FaceNet Embeddings

- **Dataset**: UTKfaces dataset.
- **Method**: Train a Neural Network using FaceNet embeddings as input features and gender as the target variable.
- **Evaluation**: Assess performance based on the loss function during training and accuracy on test sets. Compare results with other gender prediction methods.

## Tools and Technologies

- **Facial Recognition**: FaceNet
- **Datasets**: LFW, UTKfaces
- **Machine Learning**: Neural Networks
- **Metrics**: Accuracy, Precision, Recall, F1 Score

## Results and Insights

The project aims to provide insights into how facial recognition technology performs across different genders and contribute to discussions on ethical considerations and potential biases. The results will be compared with other gender prediction methods to gauge effectiveness and highlight areas for improvement.

## Getting Started

To replicate or build upon this project:

1. **Dataset Preparation**: Download and prepare the LFW and UTKfaces datasets.
2. **Environment Setup**: Install necessary libraries for facial recognition and machine learning (e.g., `tensorflow`, `scikit-learn`).
3. **Run Analyses**: Execute the provided scripts to perform the analyses and evaluate results.
