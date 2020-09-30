# Fake-And-Real-News-Detection
## Misinformation is one of the biggest issues in today's society and Fake news is a real problem

Dataset used is from Kaggle- 
https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

## Problem Statement
We have 2 datasets with Real News data and Fake News data. Each dataset has around 22000 articles. As we merge both, we have around 45000 articles of real and fake. The aim is to build a model to correctly predict if a news is real or fake.

## Table of Contents
1. [Import Packages](#import-packages)
2. [Read Data](#read-data)
    * [Create Target based on Real and Fake data](#create-target)
    * [Concat both real and fake data](#concat-data)
3. [Data Analysis](#data-analysis)
    * [Missing value Treatment](#treat-missing-value)
    * [Merge Title and Text data](#merge-title-text)
4. [Data Cleaning](#data-cleaning)
    * [Preprocessing Text to get Stemmed and Lemmatized Corpus](#Preprocess-text)
    * [WordCloud for label=1 -- Real News](#word-cloud-label-1)
    * [WordCloud for label=0 -- Fake News](#word-cloud-label-0)
5. [Classification models using CountVectorizer and TFIDF Vectorizer](#create-models)
    * [Using CountVectorizer and TFIDF Vectorizer with stemmed text](#counttfidf-stemmed)
    * [Using CountVectorizer and TFIDF Vectorizer with lemmatized text](#counttfidf-lemmatized)
6. [LSTM model using One Hot vector](#one-hot-vector-lstm)
    * [Using One hot representation and Stemmed Text](#one-hot-stemmed)
    * [Evaluate model](#stemmed-evaluate)
    * [Using One hot representation and Lemmatized Text](#one-hot-lemmatized)
    * [Evaluate model](#lemmatized-evaluate)
7. [Conclusion](#conclusion)
