# Sentiment Analysis with Recurrent Neural Networks (RNN) and LSTM

## Project Overview

This project aims to build a sentiment analysis model using supervised learning techniques with vanilla Recurrent Neural Networks (RNN) and Long Short-Term Memory networks (LSTM). The goal is to classify sentences as positive (labeled as 1) or negative (labeled as 0) based on their sentiment.

## Dataset

The dataset used for this project is the "Sentiment Labelled Sentences Dataset" sourced from the UC Irvine Machine Learning Repository. The dataset comprises sentences from three different websites: amazon.com, imdb.com, and yelp.com. Each website contributes 500 positive and 500 negative sentences, making a total of 3000 labeled sentences for analysis. The dataset was originally curated for the paper 'From Group to Individual Labels using Deep Features' by Kotzias et al., KDD 2015.

**Dataset Link:** [Sentiment Labelled Sentences Data Set](link_to_the_dataset)

## Project Deliverables

1. **Data Gathering:**
   - Gather the sentiment analysis dataset from the UCI Machine Learning Repository.
  
2. **Data Preprocessing:**
   - Tokenize the sentences.
   - Convert text to lowercase.
   - Remove stopwords using NLTK.
  
3. **Baseline Model:**
   - Implement a DummyClassifier.
   - Train the model on preprocessed data.
   - Evaluate the model's performance using accuracy, precision, recall, and F1-score metrics.

4. **Vanilla RNN Model:**
   - Implement a vanilla RNN sentiment analysis model.
   - Train the model on preprocessed data.
   - Evaluate the model's performance using accuracy, precision, recall, F1-score, and kappa.
   - Use GridSearchCV to find the best hyperparameters.

5. **LSTM Model:**
   - Implement an LSTM sentiment analysis model.
   - Train the model on preprocessed data.
   - Evaluate the model's performance using accuracy, precision, recall, F1-score, and kappa.
   - Use GridSearchCV to find the best hyperparameters.

6. **Enhanced Model:**
   - Implement an enhanced sentiment analysis model using Turing neural networks (details needed).
   - Train the model and evaluate its performance.
