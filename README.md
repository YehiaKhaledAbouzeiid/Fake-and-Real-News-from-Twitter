# Fake News Detection with Text Analysis and Machine Learning

## Project Overview

This Jupyter Notebook explores the problem of fake news detection using text analysis and machine learning techniques. It utilizes techniques like word tokenization, lemmatization, and various classifiers to distinguish between true and fake news articles.

## Data

Two CSV datasets containing text content of both true and fake news articles.

## Analysis Steps

### Data Preprocessing

1. Read and merge the two datasets.
2. Clean text data by removing punctuation, stop words, and converting to lowercase.
3. Apply Porter Stemming or WordNet Lemmatization for further normalization.
4. Separate features (text) and labels (true/fake).

### Feature Engineering

- Employ Bag-of-Words (BoW) or TF-IDF vectorization to convert text into numerical features.

### Model Training and Evaluation

- Train various machine learning classifiers like Multinomial Naive Bayes (MNB) and Random Forest Classifier (RFC) on the extracted features and labels.
- Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

### Visualization and Comparison

- Generate word clouds for both true and fake news texts to identify frequently used words.
- Compare and analyze the performance of different machine learning models.

## Key Findings

- Both MNB and RFC achieve promising accuracy scores in classifying true and fake news.
- Word clouds reveal distinct word patterns for true and fake news, such as emphasis on emotions and sensational language in fake news.
- Further analysis can involve exploring other feature engineering techniques, using deep learning models like LSTMs, and investigating the impact of news sources and article lengths on fake news detection.

## Code Summary

The code imports necessary libraries for data manipulation, text processing, and machine learning.
It reads and preprocesses the true and fake news datasets.
Applies BoW or TF-IDF vectorization to convert text into numerical features.
Trains MNB and RFC classifiers on the processed data.
Evaluates model performance using various metrics.
Generates word clouds for both categories of news.


# 

## 

* 
* 
