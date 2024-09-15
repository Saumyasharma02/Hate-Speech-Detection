# Hate-Speech-Detection
This repository contains a Hate Speech Detection Model designed to automatically classify text as either hate speech or non-hate speech. The model leverages Natural Language Processing (NLP) techniques and Machine Learning algorithms to identify harmful and abusive language from various data sources, including social media platforms, online forums, and comment sections.

## Table of Contents
* Introduction
* Features
* Dataset
* Data Visualization
* Usage
* Model Training and Evaluation
* Results
* Text Prediction

## Intoduction
Hate speech refers to any form of communication, whether spoken, written, or behavioral, that demeans, discriminates against, or incites violence or hostility towards an individual or group based on attributes such as race, religion, ethnicity, gender, sexual orientation, or other distinguishing characteristics.This project explores various machine learning models to classify tweets into one of three categories:
* Hate Speech
* Offensive Language
* Neither
* The repository provides all the necessary code for data preprocessing, model training, hyperparameter tuning, and real-time text prediction.

## Features
### 1. **Text Preprocessing**
   - **Tokenization**: Breaking down text into smaller components, like words or tokens.
   - **Stop-word Removal**: Filtering out common words (like "the", "is", etc.) that don't carry significant meaning.
   - **Stemming/Lemmatization**: Reducing words to their root forms to minimize the feature space.
   - **Lowercasing**: Converting text to lowercase for uniformity.
   - **Special Character Removal**: Eliminating punctuation, URLs, or special symbols that don't add value to the analysis.

### 2. **Feature Extraction**
   - **Bag of Words (BoW)**: Represents the text as a collection of word counts or frequencies.
   - **TF-IDF (Term Frequency-Inverse Document Frequency)**: Measures the importance of words in the dataset.
   - **Word Embeddings**: Using models like **Word2Vec**, **GloVe**, or **BERT** to capture semantic relationships between words.

### 3. **Machine Learning Models**
  * Random Forest
  * Logistic Regression
  * Decision Tree
  * Naive Bayes
    
### 4. **Hyperparameter Tuning**
   Model tuning is performed using GridSearchCV and RandomizedSearchCV to optimize accuracy.

### 5. **Text Prediction**
   Functionality to predict the category of any input text.

### 6. **Data Visualization**
  Visualizations include class distribution plots and word clouds for better understanding of the data.
   
### 7. **Evaluation Metrics**
   - **Accuracy**: Overall percentage of correctly classified instances.
   - **Precision**: How many predicted hate speech instances are actually hate speech.
   - **Recall**: How many actual hate speech instances were correctly identified.
   - **F1-Score**: A balance between precision and recall.
   - **Confusion Matrix**: To visualize the performance of the classification model.

## Dataset
The dataset used for this project is the Hate Speech and Offensive Language Dataset, available from Kaggle. The dataset consists of tweets labeled into three categories:
* 0: Hate Speech
* 1: Offensive Language
* 2: Neither

## Data Visualization
![Class Distribution](images/logo.png)

