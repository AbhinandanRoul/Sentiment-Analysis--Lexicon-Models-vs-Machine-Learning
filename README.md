# Sentiment-Analysis--Lexicon-Models-vs-Machine-Learning
An experiment to find out the performance between unsupervised Lexical methods and supervised ML in Sentiment Analysis
## For Unsupervised Lexical Methods-
### AFINN Lexicon
AFINN Lexicon is the most simplest and popular lexicons for sentiment analysis. The current version is AFINN-en-165.txt and it contains 3382 words along with it’s polarity score. <br>
## SentiWordNet
entiWordNet is a lexical resource for opinion mining. SentiWordNet assigns to each synset of WordNet three sentiment scores: positivity, negativity, objectivity.<br>
## VADER
ADER (Valence Aware Dictionary and Sentiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. It is fully open-sourced and is available in the NLTK package which can be applied directly to unlabelled text data. VADER is capable of detection of polarity and intensity of emotion.<br>
## For Supervised ML method
### Bag of Word Model<br>
A Bag of words model is a method of extracting features from text for ML modelling. In BOW the words in a text are extracted and a list of all the words and their frequency are made. In other words, a dictionary of all the words containing in the text is created. It is known as a Bag of words because the structure of words and their meaning in the context are removed.
### Term Frequency-Inverse Document Frequency (TF-IDF)<br>
The central idea behind TF-IDF is to provide more importance to words that occur more frequently in a document than to words with lesser occurrence. Here, Term Frequency refers to the frequency of each term.

## My observations
We find that AFINN lexical model has better accuracy (72%)than other lexical models. It is found that other models’ performance is close to AFINN on the given data.
In case of Supervised Learning models Logistic Regression model on Bag of Word model features, is the best as it is having an accuracy of 89.94%.
