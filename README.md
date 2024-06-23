# Text-Classification-for-Spam-and-Ham-SMS-Messages
This project aims to build a machine learning model that classifies SMS messages as either spam or ham (non-spam). It involves data preprocessing, vectorization, model training, and evaluation, along with comparisons of different models to find the best performer.

## Introduction
The objective of this project is to develop a robust text classification model to identify spam SMS messages. By leveraging natural language processing (NLP) techniques and machine learning algorithms, we aim to achieve high accuracy in distinguishing spam from ham messages.

## Dataset
The dataset used in this project consists of SMS messages labeled as spam or ham. Each entry includes:

**Category:** The label indicating whether the message is spam or ham.

**Message:** The content of the SMS message.

## Features
**Data Exploration and Visualization:** Understanding the distribution and characteristics of the dataset with visual tools.

**Data Preprocessing:** Converting text to lowercase, removing punctuation, tokenizing, removing stopwords, and lemmatization.

**Vectorization:** Using CountVectorizer to convert text data into numerical format.

**Model Training and Evaluation:** Training a Multinomial Naive Bayes classifier and evaluating its performance with confusion matrix and classification report.

**Model Comparison:** Evaluating different models such as Logistic Regression, SVM, and Random Forest.

## Results
The Multinomial Naive Bayes classifier achieved good performance in classifying SMS messages.
