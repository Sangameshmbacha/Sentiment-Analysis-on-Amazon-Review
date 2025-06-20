Sentiment Analysis on Amazon Review using NLTK 

This project performs sentiment analysis on Amazon product reviews using the NLTK library in Python. It classifies the sentiment of customer reviews as Positive or Negative based on their textual content.

Project Overview:

Load Amazon review dataset.
Preprocess the text using NLP techniques:
Tokenization
Stopwords removal
Lemmatization
Use VADER (Valence Aware Dictionary and sEntiment Reasoner) from NLTK to analyze sentiment.
Compare predicted sentiment with actual labels.
Generate a classification report and confusion matrix.

Libraries Used:

pandas,
nltk,
sklearn

Output:

Confusion Matrix: Shows how many reviews were correctly/incorrectly classified.
Classification Report: Displays precision, recall, F1-score, and support for each class.
