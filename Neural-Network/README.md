# Task 3 – EMNIST Character Classification

## Overview
This task focuses on image classification using the EMNIST dataset. The objective was to build a supervised learning model capable of classifying handwritten characters by training on pixel-based image data.

## Problem Statement
The EMNIST dataset consists of grayscale images representing handwritten characters. The task is formulated as a multi-class classification problem, where each image must be correctly assigned to its corresponding character label.

## Data Preparation
The following preprocessing steps were applied:

- Loading the EMNIST dataset
- Reshaping image data into appropriate input format
- Normalizing pixel values for stable training
- Splitting data into training and testing sets

Proper normalization ensures that pixel intensity values are scaled consistently, improving model convergence.

## Modeling Approach
A neural network-based classifier was implemented to learn patterns from image pixel data.

The model learns to:

- Extract meaningful features from pixel inputs
- Minimize classification error using supervised learning
- Predict the correct character label

## Evaluation
Model performance was evaluated using:

- Accuracy score
- Training and validation performance monitoring

Classification accuracy was used as the primary metric to assess model effectiveness in recognizing handwritten characters.

## Key Learning Outcomes
- Understanding image-based classification tasks
- Working with high-dimensional pixel data
- Implementing neural network models for multi-class problems
- Evaluating classification performance in computer vision tasks

## Conclusion
This task strengthened practical understanding of image classification workflows, including preprocessing image data, training neural networks, and evaluating performance on unseen data.
