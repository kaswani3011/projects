# twitter sentiment analysis using NLP and ML
# Overview
This project performs sentiment analysis on Twitter data using a multi-step process. It involves splitting the dataset into training and testing data, preprocessing the tweets, and finally conducting sentiment analysis.

# Steps to Perform Twitter Sentiment Analysis
Split Dataset:

Run the file train-test-split.py to split the Twitter dataset into training and testing data.
bash
Copy code
python train-test-split.py
Preprocessing:

Run the file preprocessing.py to preprocess the tweets:
Remove @user mentions
Remove non-alphabetic characters, spaces, and apostrophes
Remove links
Remove single characters
Remove stopwords
Lemmatize and stem words
Files Overview
train-test-split.py: Splits the Twitter dataset into training and testing data.
preprocessing.py: Preprocesses the tweets by removing mentions, links, and other non-alphanumeric characters, and performs lemmatization and stemming.
sentiment-analysis.py: Conducts sentiment analysis on the preprocessed tweets to classify them as positive, negative, or neutral.
# Usage
Clone the repository to your local machine.
Navigate to the project directory.
Run train-test-split.py to split the dataset.
Run preprocessing.py to preprocess the tweets.
Perform sentiment analysis using sentiment-analysis.py.
# Dependencies
Python 3.x
NLTK
