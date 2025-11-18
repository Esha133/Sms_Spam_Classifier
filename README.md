This project is a beginner-friendly Machine Learning model that classifies text messages as Spam or Ham (Not Spam) using simple and understandable steps.
It covers data cleaning, preprocessing, EDA, vectorization, model training, evaluation, and prediction
The goal of this project is to build a machine learning model that can detect whether a message is spam or not spam.
We use the SMS Spam Collection Dataset which contains 5,572 labeled messages.

This project includes:

Data loading

Preprocessing

Exploratory Data Analysis (EDA)

Text vectorization

Model training

Performance comparison

Predictions on custom messages

Dataset:

Name: SMS Spam Collection Dataset

Classes:

ham → not spam

spam → spam message

Technologies & Libraries Used

Python

pandas

numpy

matplotlib

seaborn

sklearn

nltk

wordcloud

 Data Preprocessing Steps

 Removed duplicates
 Removed missing values
 Text cleaned using:

Lowercasing

Tokenization

Removing stopwords

Removing punctuation

Stemming (PorterStemmer)

Created a transformed_text column

Exploratory Data Analysis (EDA)

Countplot of Spam vs Ham messages

Distribution of message lengths

WordClouds for Spam and Ham

Most common 30 words (Spam & Ham)
