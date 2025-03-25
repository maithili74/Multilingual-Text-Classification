# Multilingual-Text-Classification

## Project Overview

This project focuses on building a toxic comment classification model using a combination of traditional machine learning models and deep learning models. The objective is to predict whether a given comment is toxic or not. We leveraged Word2Vec embeddings for feature extraction and applied various classification models to achieve the highest accuracy.

## Main Concepts

Data Processing: Cleaned and preprocessed multilingual text data, tokenized it, and transformed it into word embeddings using Word2Vec.
Traditional Models: Implemented and evaluated Logistic Regression and Random Forest models, achieving 83% accuracy.
Deep Learning Models: Used MLP (Multilayer Perceptron), RNN, and LSTM models, achieving 85% accuracy.
Class Imbalance Handling: Addressed class imbalance in the training data using SMOTE to generate synthetic samples.

## Data

The dataset used for the code is atken from kaggale. It contains comments in multiple languages, with a binary label indicating whether the comment is toxic (1) or not toxic (0). The dataset was split into three parts:
Train: Used for model training and balancing.
Validation: Used for evaluating model performance during training.
Test: Used for final evaluation of the models.

## Models Used

* Logistic Regression
* Random Forest
* MLP (Multilayer Perceptron)
* RNN (Recurrent Neural Network)
* LSTM (Long Short-Term Memory)

## Results:

Logistic Regression and Random Forest: Achieved 82% accuracy.
Deep Learning Models (MLP, RNN, LSTM): Achieved 85% accuracy, improving model performance by effectively capturing sequential text patterns.


