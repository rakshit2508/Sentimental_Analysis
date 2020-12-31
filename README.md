# Sentimental_Analysis
## Project -
The aim is to predict the sentiment of the review(Positive or negative) using NLP and Machine Learning Models.

## About Data -
 The sample dataset consists of 1000 reviews from an un-named restaurant.

## Process followed
At first, we need to do text cleaning. It involves:

#### Removing punctuations(In our case we will not remove apostrophe as it is used in negation words like didn't isn't etc, that shows sentiment)
#### Removing stopwords like articles, prounouns etc.(Here we will exclude the stopwords that will indicate sentiments like no, not etc.
#### Changing our case to lower case
#### Stemming the words in order to get the root of the word.(This is done to optimise the sparse matrix that will be formed by the CountVectoriser)
#### Making the Bag Of Words Model by using the CountVectoriser class imported from sklearn.

## Building Classification model.
Here I used three models:

#### Logistic Regression
#### Naive Bayes
#### SVM

## Conclusion
#### Logistic regression gave the best performance with 82% accuracy.
