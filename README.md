# Neural Network and Machine Learning Assignments

## Overview

This repository contains implementations of fundamental machine learning and neural network algorithms using Python and NumPy. The assignments focus on understanding the mathematical foundations and implementing models **from scratch without using built-in ML algorithms**.

The tasks include implementations of perceptrons, logistic regression, linear regression, and multilayer perceptrons with backpropagation.

---

# Assignment 1: Perceptron for Logic Gates

## Objective

Design and implement a perceptron model to simulate basic logic gates.

## Gates Implemented

* AND Gate
* OR Gate
* NAND Gate
* NOR Gate

## Description

A perceptron is the simplest form of a neural network used for binary classification. In this assignment, perceptron weights and biases are selected such that the model reproduces the behavior of logical operations.

The perceptron computes:

y = f(w1x1 + w2x2 + b)

Where:

* x1, x2 are inputs
* w1, w2 are weights
* b is bias
* f is a step activation function

## Technologies Used

* Python
* NumPy

---

# Assignment 2: Logistic Regression using Single Layer Perceptron

## Objective

Implement logistic regression using a single layer perceptron neural network for classification.

## Dataset

Glass Identification Dataset

Dataset Link
https://www.kaggle.com/datasets/uciml/glass

## Description

The glass dataset contains chemical composition information of different types of glass. Logistic regression is implemented using a sigmoid activation function and gradient descent to classify glass samples.

Steps involved:

1. Load dataset
2. Preprocess and normalize features
3. Train model using gradient descent
4. Predict class labels
5. Evaluate model accuracy

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn (for preprocessing and train-test split)

---

# Assignment 3: Multiple Linear Regression using Perceptron

## Objective

Implement multiple linear regression using a perceptron-based learning approach.

## Dataset

Multiple Linear Regression Dataset

Dataset Link
https://www.kaggle.com/datasets/hussainnasirkhan/multiple-linear-regression-dataset

## Description

Multiple linear regression predicts a continuous output using multiple input variables. The model learns optimal weights using gradient descent to minimize prediction error.

General model:

y = w1x1 + w2x2 + ... + wnxn + b

Steps involved:

1. Load dataset
2. Normalize input features
3. Train regression model
4. Predict test values
5. Compute Mean Squared Error (MSE)

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

---

# Assignment 4: Multilayer Perceptron with Backpropagation

## Objective

Implement a Multilayer Perceptron (MLP) and train it using the backpropagation algorithm.

## Dataset

Abalone Dataset

Dataset Link
https://archive.ics.uci.edu/dataset/1/abalone

## Description

The goal of this assignment is to predict the age of abalone based on physical measurements such as length, diameter, and weight.

The neural network consists of:

* Input layer
* Hidden layer
* Output layer

Backpropagation is used to update weights by minimizing the mean squared error between predicted and actual values.

Steps involved:

1. Data preprocessing
2. One-hot encoding of categorical variables
3. Forward propagation
4. Loss computation
5. Backpropagation
6. Weight updates using gradient descent

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

---

# Requirements

Install the required Python libraries:

pip install numpy pandas scikit-learn

---

# How to Run

1. Clone the repository
2. Download datasets if required
3. Run each Python script

Example:

python perceptron_logic_gates.py
python logistic_regression_glass.py
python multiple_linear_regression.py
python mlp_backpropagation_abalone.py

---

# Learning Outcomes

After completing these assignments, the following concepts are understood:

* Perceptron learning algorithm
* Logistic regression using neural networks
* Multiple linear regression implementation
* Multilayer perceptron architecture
* Backpropagation algorithm
* Gradient descent optimization

---

# Author

Anshul Kaushal
Computer Engineering Student
