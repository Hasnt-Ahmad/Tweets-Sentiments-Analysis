# Tweets-Sentiments-Analysis
Twitter Sentiment Analysis NLP
**Twitter Sentiment Analysis Using NLP and Machine Learning**
  This project demonstrates the application of Natural Language Processing (NLP) and machine learning techniques to analyze sentiment in Twitter tweets. The focus is on building a text classification model that can distinguish between positive and negative sentiments in tweets.

**Project Overview**
  The dataset used in this project consists of Twitter tweets, which are labeled as either positive (target = 1) or negative (target = 0). The data is preprocessed and cleaned using NLP techniques such as tokenization, lemmatization, and stop word removal, powered by the spaCy library.

**Key Steps**
**1.**Data Preprocessing:****
Loaded and cleaned the dataset, keeping only the target and text columns.
Balanced the dataset by sampling an equal number of positive and negative tweets.
Preprocessed the text data using spaCy to remove stop words and punctuation, and lemmatize the tokens.

**2.Feature Engineering:**
Created TF-IDF features to represent the text data numerically.
Additionally, n-grams (up to bi-grams) were generated to capture word combinations.

**3.Modeling:**
Applied the Multinomial Naive Bayes algorithm to train the sentiment classification model.
Performed model training and evaluation on both the TF-IDF features and n-gram features.

**4.Evaluation:**
Assessed the model's performance using accuracy and classification report metrics.

**5.Results**
The model was evaluated based on its accuracy and detailed classification metrics, highlighting its effectiveness in distinguishing between positive and negative sentiments in tweets.

**How to Run**
Clone the repository.
Install the necessary dependencies.
Run the provided notebook or script to preprocess the data, train the model, and evaluate the results.
Requirements
Python 3.x
pandas
numpy
spaCy
scikit-learn

**Conclusion**
This project provides a simple yet effective approach to performing sentiment analysis on Twitter data using NLP and machine learning. It can serve as a foundation for more advanced text analytics tasks.
