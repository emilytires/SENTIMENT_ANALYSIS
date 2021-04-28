# SENTIMENT_ANALYSIS

Sentiment analysis is a natural language processing (NLP) technique used to determine whether data is positive, negative or neutral. Sentiment analysis models focus on polarity (positive, negative, neutral) but also on feelings and emotions (angry, happy, sad, etc), urgency (urgent, not urgent) and even intentions (interested v. not interested).

Sentiment Analysis Approaches

1. Machine Learning Based Approach

  1.1. Linear Classifiers (SVM, Neural Network)

  1.2. Decision Tree Classifiers

  1.3. Probabilistic Classifiers (Naive Bayes, Bayesian Network)

2. Lexicon - Based Approach

  2.1. Dictionary Based Approach
  
  2.2. Corpus Based Approach

3. Hybrid Approach


## Steps of Sentiment Analysis

* Data Preprocessing

  *   Normalizing Case Folding
  *   Drop Punctuations
  *   Drop Numbers
  *   Drop Stopwords
  *   Drop RareWords
  *   Lemmatization

* Data Visualization

  *   Wordcloud

* Modelling

  * Feature Engineering 

    *   Finding Polaritiy Score using SentimentIntensityAnalyzer
    *   Convert Label Encoding to polarity score segment
    *   Count Vectors
    *   TF-IDF Word Level
    *   TF-IDF N-Gram Level
    *   TF-IDF Characters Level

  * Sentiment Modelling using Random Forest Classifier

    *   TF-IDF Word-Level Random Forest Regression
    *   TF-IDF N-GRAM Random Forest Regression
    *   TF-IDF CHARLEVEL Random Forest Regression
    *   Count Vectors Random Forest Regression 
