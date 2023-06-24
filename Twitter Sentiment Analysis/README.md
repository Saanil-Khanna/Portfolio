# Twitter Sentiment Analysis

This repository contains a Python script for performing sentiment analysis on Twitter data using machine learning techniques.

## Overview

The purpose of this project is to analyze the sentiment of tweets and classify them into different sentiment categories such as positive, negative, or neutral. The analysis is performed using various machine learning classifiers and includes data preprocessing, feature extraction, model training, and evaluation.

## Features

- Loads training and validation data from CSV files.
- Performs exploratory data analysis to understand the data distribution and identify any data quality issues.
- Preprocesses the tweet content by converting to lowercase, removing stopwords, and applying stemming.
- Constructs TF-IDF feature vectors from the preprocessed text data.
- Trains a random forest classifier on the training data.
- Evaluates the trained model using the validation data and generates a classification report.
- Visualizes the evaluation results with a confusion matrix.

## Prerequisites

- Python 3.x
- Libraries: numpy, pandas, nltk, scikit-learn, seaborn, matplotlib

## Usage

Prepare the data:

Place your training and validation data in CSV format in the appropriate location (e.g., data/twitter_training.csv and data/twitter_validation.csv).
Ensure that the CSV files have the required columns.
Run the script: python sentiment_analysis.py

View the results:

The script will display information about the data, preprocess the text data, train the model, and evaluate the model's performance.
The classification report and confusion matrix will be displayed, providing insights into the model's accuracy and performance.


## License
This project is licensed under the MIT License.

## Acknowledgements
The code in this repository was developed based on the principles and techniques of sentiment analysis, machine learning, and natural language processing. The following resources were referenced during the development process:

NLTK Documentation,
Scikit-learn Documentation,
Seaborn Documentation,
Python Programming Language






