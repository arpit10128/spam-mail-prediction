# spam-mail-prediction

## Overview

This project implements a machine learning-based spam email classification system using Natural Language Processing (NLP) techniques. The model analyzes email content and predicts whether a message is Spam or Ham (Legitimate Email).

## Features

* Text preprocessing and cleaning
* TF-IDF feature extraction
* Logistic Regression classifier
* Real-time spam prediction
* Model evaluation using accuracy metrics

## Dataset

* Spam Mail Dataset
* Approximately 5,500 labeled email messages
* Classes:

  * Spam
  * Ham

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* TF-IDF Vectorizer

## Machine Learning Pipeline

1. Data Loading
2. Data Cleaning and Preprocessing
3. Text Vectorization using TF-IDF
4. Train-Test Split
5. Logistic Regression Model Training
6. Model Evaluation
7. Spam Prediction

## Results

* Training Accuracy: 96.77%
* Test Accuracy: 96.68%

## Future Improvements

* Implement Naive Bayes and SVM classifiers
* Add F1-Score, Precision, and Recall evaluation
* Deploy as a web application using Flask or FastAPI
* Integrate advanced NLP models such as BERT
