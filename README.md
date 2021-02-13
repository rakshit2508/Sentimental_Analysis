# Sentimental_Analysis
## Project -
The aim is to predict the sentiment of the review(Positive or negative) using NLP and Machine Learning Models.

## About Data -
  The dataset which contains 40k movie reviews from IMDB, we see that there are two prominent columns. One being TEXT which contains the criticism and the other being LABEL which contains the O’s and 1’s, where 0-NEGATIVE and 1-POSITIVE..

## Process followed
At first, we need to do text cleaning. It involves:

 * Removing punctuations(In our case we will not remove apostrophe as it is used in negation words like didn't isn't etc, that shows sentiment)
 * Removing stopwords like articles, prounouns etc.(Here we will exclude the stopwords that will indicate sentiments like no, not etc.
 * Changing our case to lower case
 * Stemming the words in order to get the root of the word.(This is done to optimise the sparse matrix that will be formed by the CountVectoriser)
 * TF-IDF Vertorizer is used to convert the raw documents into feature matrix.

## Building Classification model.
Here I used the model:

* Logistic Regression


## Conclusion
#### Logistic regression gave the best performance with 89% accuracy.
