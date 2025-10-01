# ASSIGNMENT-1
Project Overview
This project implements an Artificial Neural Network (ANN) to predict bank customer churn using the Churn_Modelling dataset. The model is built using Keras with a TensorFlow backend and aims to classify whether a customer will leave the bank based on various features.

Dataset
File: Churn_Modelling.csv

Features: 11 input variables including customer demographics, account information, and banking activities

Target: Binary classification (1 = Customer exits, 0 = Customer stays)

Model Architecture
The ANN consists of:

Input Layer: 11 neurons (matching the number of features)

Hidden Layers:

First hidden layer: 6 neurons with ReLU activation

Second hidden layer: 6 neurons with ReLU activation

Output Layer: 1 neuron with Sigmoid activation for binary classification

Training Parameters
Optimizer: Adam

Loss Function: Binary Crossentropy

Batch Size: 10

Epochs: 100

Train-Test Split: 80-20

Results
The model achieved:

Training Accuracy: ~86%

Confusion Matrix on test set:

True Negatives: 1494

False Positives: 101

False Negatives: 187

True Positives: 218

Usage
The notebook includes:

Data preprocessing and feature engineering

Model building and training

Prediction on test data

Single customer prediction example

Performance evaluation using confusion matrix

Dependencies
numpy

matplotlib

pandas

scikit-learn

keras

tensorflow

How to Run
Execute the cells sequentially in the Jupyter notebook to:

Load and preprocess the data

Train the neural network model

Make predictions and evaluate performance

The model can be used to predict customer churn for new data by providing the required feature values in the specified format.
