# SPAM-EMAIL-CLASSIFIER
This project aims to classify emails as Spam or Non-Spam (Ham) using machine learning techniques. The model is built using Naive Bayes, a popular algorithm for text classification tasks, and Scikit-learn for machine learning operations.
In this project, I use a dataset containing text messages labeled as either Spam or Ham. The goal is to build a machine learning model to classify new email messages as spam or non-spam using Natural Language Processing (NLP) techniques.

Data Cleaning: Extracts relevant columns and handles missing values.
Text Vectorization: Converts the text messages into a numeric format using CountVectorizer.
Model: Multinomial Naive Bayes classifier is used to train the model.
Evaluation: The model is evaluated on accuracy and a confusion matrix to measure its performance.
Model Training
The model training process involves the following steps:

Data Preprocessing:

We clean the dataset by selecting only relevant columns (Label and Message).
Labels are encoded as 0 for Ham and 1 for Spam.
Feature Extraction:

CountVectorizer is used to convert the text messages into a numerical format that can be fed into the machine learning model.
Modeling:

Multinomial Naive Bayes is used for classification, which is well-suited for text data.
Evaluation:

Accuracy and confusion matrix are calculated to evaluate the model's performance.
