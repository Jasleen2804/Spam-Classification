# Spam-Classification
This project implements a text classification pipeline to distinguish between "ham" (legitimate) and "spam" (unwanted/junk) SMS messages using fundamental concepts of Natural Language Processing and Machine Learning.

## Project Goal
The primary objective is to train a highly accurate classification model (Multinomial Naive Bayes) capable of automatically filtering incoming SMS messages. The final model achieved an accuracy of approximately 97%.

##  Technology Stack
Language: Python

Data Analysis: Pandas

NLP & Preprocessing: NLTK (PorterStemmer, stopwords)

Machine Learning: Scikit-learn (TfidfVectorizer, MultinomialNB, train_test_split, accuracy_score)

Visualization: Matplotlib

## Dataset
The project uses the spam.csv dataset, which contains a collection of SMS messages labeled as either ham or spam.

## How to Run
(Note: This project was designed to run in an environment like Google Colab where the NLTK data and dataset paths are pre-configured.)

1. Ensure you have the required libraries installed:

pip install pandas nltk scikit-learn matplotlib


2. Download the spam.csv dataset and place it in the appropriate path (/content/sample_data/ in the original notebook, or adjust the path to your local environment).

3. Execute the provided Python code cells sequentially.


