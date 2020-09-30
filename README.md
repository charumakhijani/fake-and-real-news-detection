# Fake-And-Real-News-Detection
Dataset used is from Kaggle- 
https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

## Problem Statement
We have 2 datasets with Real News data and Fake News data. Each dataset has around 22000 articles. As we merge both, we have around 45000 articles of real and fake. The aim is to build a model to correctly predict if a news is real or fake.

## Table of Contents
1. Import Packages
2. Read Data
  a. Create Target based on Real and Fake data
  b. Concat both real and fake data
3. Data Analysis
  a. Missing value Treatment
  b. Merge Title and Text data
4. Data Cleaning
  a. Preprocessing Text to get Stemmed and Lemmatized Corpus
  b. WordCloud for label=1 -- Real News
  c. WordCloud for label=0 -- Fake News
5. Classification models using CountVectorizer and TFIDF Vectorizer
  a. Using CountVectorizer and TFIDF Vectorizer with stemmed text
  b. Using CountVectorizer and TFIDF Vectorizer with lemmatized text
6. LSTM model using One Hot vector
  a. Using One hot representation and Stemmed Text
  b. Evaluate model
  c. Using One hot representation and Lemmatized Text
  d. Evaluate model
7. Conclusion
