SMS Spam Classification

This repository contains code for a spam classification model aimed at SMS messages. The model utilizes natural language processing (NLP) techniques and the Random Forest algorithm to classify messages as spam or non-spam.
Dataset

The dataset used for training and testing is the SMS Spam Collection, a public set of labeled SMS messages collected for mobile phone spam research.
Preprocessing

    Stop words and punctuation were removed using NLTK.
    Porter stemming was applied to the remaining words.
    The data was split into training and testing sets.

Model Training

    Bag-of-words representation was created using CountVectorizer from scikit-learn.
    Random Forest classifier was trained on the training data.

Evaluation

    Confusion matrix and evaluation metrics including precision, recall, and F1-score are provided.
    The model achieved an accuracy of 98%.

Files

    spam_classification.ipynb: Jupyter notebook containing the code implementation.
    sms_spam_collection.csv: SMS Spam Collection dataset.

Usage

    Clone the repository.
    Install the required dependencies.
    Run the Jupyter notebook spam_classification.ipynb to train and evaluate the model.

Requirements

    Python 3.x
    scikit-learn
    NLTK
    Jupyter notebook
