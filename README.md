# Deep Learning Image Classification

This repository contains a deep learning project that implements a Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset.

## Project Overview
- **Objective:** Build and train a CNN to classify images from the CIFAR-10 dataset.
- **Dataset:** The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes.
- **Models Implemented:** 
  - **Baseline Model:** A simple fully connected neural network for comparison.
  - **CNN Model:** A custom CNN featuring convolutional layers, max pooling, batch normalization, and dropout regularization.

## Features
- Data preprocessing (normalization and one-hot encoding of labels).
- Model training with evaluation metrics.
- Visualization of training history and prediction results.
- Detailed classification report and performance comparison between models.

## Installation
1. **Prerequisites:** Python 3.7+  
2. **Install Dependencies:**
   ```bash
   pip install numpy matplotlib tensorflow scikit-learn
   ```
3. (Optional) Create a virtual environment.

## Project Structure
- **8175_assignment4.ipynb:** Main notebook containing data preparation, model definitions, training routines, and evaluation.
- **README.md:** This documentation file.

## How to Run
1. Open the notebook (8175_assignment4.ipynb) in Jupyter or your preferred environment.
2. Execute the cells sequentially to preprocess the data, build the models, and evaluate their performance.

## Results
- Training history graphs for both accuracy and loss.
- A comprehensive classification report.
- Visualizations of sample predictions with correct and incorrect labels highlighted.


## Acknowledgements
- CIFAR-10 dataset courtesy of the University of Toronto.
- TensorFlow and Keras for making deep learning accessible.
