# Task 3 – EMNIST Character Classification

## Overview
This task focuses on multi-class image classification using the EMNIST dataset. The objective was to build a supervised learning model capable of classifying handwritten characters based on pixel-level image data.

## Problem Statement
The EMNIST dataset consists of grayscale images representing handwritten characters. The task is formulated as a multi-class classification problem where each image must be assigned to its correct character label.

## Data Preparation
The following preprocessing steps were applied:

- Loading the EMNIST dataset
- Reshaping image data into flattened vector format
- Normalizing pixel intensity values
- Splitting data into training and testing sets

Normalization ensures consistent pixel scaling and supports stable model training.

## Modeling Approach
A feedforward neural network (fully connected architecture) was implemented using flattened grayscale image inputs.

The model was trained to:
- Learn classification boundaries from pixel features
- Minimize categorical classification error
- Predict the correct character class label

## Evaluation
Model performance was evaluated using:

- Classification accuracy on the test set

Accuracy was used as the primary metric to assess recognition performance.

## Key Learning Outcomes
- Working with high-dimensional image data
- Preparing image datasets for neural network training
- Implementing multi-class classification models
- Evaluating performance of deep learning models

## Conclusion
This task reinforced foundational concepts in image classification, neural network training, and performance evaluation under time-constrained exam conditions.
