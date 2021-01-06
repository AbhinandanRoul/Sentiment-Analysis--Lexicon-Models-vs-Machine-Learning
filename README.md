# Sentiment-Analysis--Lexicon-Models-vs-Machine-Learning
An experiment to find out the performance between unsupervised Lexical methods and supervised ML in Sentiment Analysis
## For Unsupervised Lexical Methods-
- AFINN Lexicon
- SentiWordNet
- VADER
## For Supervised ML method
- Bag of Word Model<br>
A Bag of words model is a method of extracting features from text for ML modelling. In BOW the words in a text are extracted and a list of all the words and their frequency are made. In other words, a dictionary of all the words containing in the text is created. It is known as a Bag of words because the structure of words and their meaning in the context are removed.
- Term Frequency-Inverse Document Frequency (TF-IDF)<br>
The central idea behind TF-IDF is to provide more importance to words that occur more frequently in a document than to words with lesser occurrence. Here, Term Frequency refers to the frequency of each term.

We find that AFINN lexical model has better accuracy (72%)than other lexical models. It is found that other models’ performance is close to AFINN on the given data.
In case of Supervised Learning models Logistic Regression model on Bag of Word model features, is the best as it is having an accuracy of 89.94%.
