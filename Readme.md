# 🍅 Tomato Leaf Disease Classification Project 🌿

## Overview

This repository contains the code and documentation for a project focused on classifying tomato leaf diseases using Convolutional Neural Networks (CNNs). The project utilizes a dataset with images of tomato leaves affected by various diseases, aiming to build a model that can accurately identify and classify these diseases.

## Features

- **Data Preprocessing**: Utilized ImageDataGenerator for preprocessing images, including rescaling, shearing, zooming, and horizontal flipping. Split the dataset into training, validation, and test sets.
- **CNN Model Building**: Constructed a Convolutional Neural Network with multiple layers, including convolutional layers, max-pooling layers, and dense layers.
- **Training and Evaluation**: Trained the model on the training set and evaluated its performance on the test set. Used early stopping to prevent overfitting.
- **Confusion Matrix and Metrics**: Generated a confusion matrix and calculated overall accuracy, precision, and F1 score. Visualized the results for better interpretation.
- **Training History Visualization**: Plotted training and validation accuracy, as well as loss, over epochs to analyze the model's learning progress.

## Technologies Used

- Python 🐍
- TensorFlow 🤖
- Keras 🧠
- Matplotlib 📊
- Scikit-learn 🧠

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Saifix/Tomato-Leaf-Diseas-Detection---DL.git



2. data
- `tomato/train/` <!-- Training set images -->
- `tomato/val/` <!-- Test set images -->
