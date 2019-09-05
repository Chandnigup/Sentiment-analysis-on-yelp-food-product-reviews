# Sentiment-analysis-on-yelp-food-product-reviews
# Table of Contents
# Introduction
This project includes the implementation of machine leaning algorithms for the classification of product reviews. There are several applications of document clustering such as sentiment analysis, spam filtering, pattern recognition etc. The provided training dataset consists of product reviews for which the following tasks have been performed for classification intentions. The following procedures are:

1. Pre-processing followed by feature generation
2. Model creation
3. Prediction on unseen data

The implementation of the code is carried out using the datasets:
1. Training data - train_data.csv
2. Testing data – test_data.csv
3. Training labels (Target variable (dependant variable)) – train_labels.csv

#### Feature Generation
Feature generation was carried out using the following:
* Tokenization
* Generating bi-grams and tri-grams
* POS Tagging
* L2 Regularisation – normalisation of vectors
* Stopwords removal

#### Models Used
For model creation we used the features df [‘Text’], train_labels[‘label] dataset for training the dataset and tested the model on the subset of the training labels in order to confirm the model accuracy. We predicted the 5 classes using 3 models namely:
* Linear support Vector Classifier
* Multiclass Logistic Regression
* Multinomial NB

# Getting Started
## Built With
* [Python](https://www.python.org/downloads/)
## Prerequisites
* pandas
* nltk
* re
* numpy
* nltk
* itertools
* sklearn
