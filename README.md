Twitter Sentiment Analysis using NLP

roject Overview :-

This project focuses on Sentiment Analysis of Twitter data using Natural Language Processing (NLP) techniques.
The goal is to automatically classify tweets as Positive or Negative based on the text content.

The project demonstrates the end-to-end NLP pipeline, including text cleaning, vectorization, model training, and sentiment prediction.

Problem Statement :-

Social media platforms like Twitter generate massive amounts of text data daily.
Analyzing sentiment from tweets helps businesses and organizations understand:
Public opinion
Customer feedback
Brand perception
This project builds a machine learning model that predicts the sentiment of a tweet.

Dataset Description :-

Dataset contains tweets and sentiment labels
Target variable:
   * 0 → Negative
   * 1 → Positive
Duplicate tweets are removed
Sentiment labels are standardized

Data Preprocessing Steps :-

The following NLP preprocessing steps are applied:
Lowercasing text
Removing URLs, mentions, hashtags
Removing punctuation and numbers
Tokenization
Stopword removal
Padding sequences for model input

Feature Engineering :-

Text is converted into numerical form using:
Tokenization
Sequence padding
This enables the model to understand and learn from textual data.

Model Building :-

A neural network–based NLP model is used
Binary classification setup
Sigmoid activation function for final output

Model Evaluation :-

Model predicts sentiment probability
Threshold of 0.5 is used for classification

Results & Insights :-

* The model successfully classifies tweet sentiment
* Works well for short informal text
* Demonstrates practical NLP pipeline implementation
