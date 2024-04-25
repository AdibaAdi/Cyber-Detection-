## Modern Low Footprint Cyber Attack Detection

This repository contains the implementation of a network intrusion detection system designed to identify malicious activities within network traffic. The project utilizes various machine learning models to differentiate between normal and malicious connections, addressing the challenge of modern low footprint cyber attacks.

## Project Overview

The aim of this project is to develop a predictive model that classifies network connections as either normal or intrusions. We use the UNSW-NB15 dataset, which reflects modern attack behaviors and normal activities, to train and test our models. This project is a part of Sac State course CSC180 Intelligent Systems by Professor Anna Baynes. 

## Models Used

We employ several machine learning models provided by scikit-learn and TensorFlow:

    Logistic Regression
    Support Vector Machine
    Fully-Connected Neural Networks
    Convolutional Neural Networks

Each model's performance is evaluated based on recall, precision, and F1-score. We also plot confusion matrices and ROC curves for a comprehensive analysis.

## Dataset

The project uses the UNSW-NB15 dataset, specifically the training and testing sets available via Canvas. This dataset includes a mix of real normal activities and synthetic attack behaviors across multiple categories.

## Requirements

Ensure all categorical values in the training data match those in the test data, and preprocess the data by encoding categorical features and normalizing numeric features. For neural network models, utilize EarlyStopping and ModelCheckpoint during training.
