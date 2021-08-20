# Sentiment-Analysis

This project is used to classify the sentiment of a given tweet/sentence using machine learning approaches on Twitter data. The methods used in this project are Textblob and Naive Bayes classifiers. 
Using Textblob, a given tweet can be categorized into seven categories based on polarity value which lies between -1(strongly negative) and 1(strongly positive). 
For the training purpose in the Naive Bayes Classifier, real-time latest 3000 positive and 3000 negative Twitter tweets have been collected using Twitter API, Tweepy. Data can be divided into a 70:30 or 80:20 ratio for training and testing purposes. After getting the features, the Naive Bayes classifier is trained on the training data. 
For the interpretability purpose, the most important features have been shown by the model. Finally, on a random piece of sentence/tweet, the model classifies that the given piece of text is either positive or negative. 

