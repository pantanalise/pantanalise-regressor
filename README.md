# BERT Regressor for twitter like and retweet prediction

This is the code to train a model for regression with BERT so that it predcits "Engagement".

## Engagement Metric

The engagement metric was created to simplify the problem by having a single value that represents both likes and retweets.

By getting the average number of likes and dividing by the average number of retweets we got that on average a post gets eight times more likes than retweets.

Since reach is way more important that likeness for a business, we decided that engagement would be the number of likes summed to eight times the number of retweets.

## Requirements
    torch
    transformers
    nltk
    scikit-learn
    matplotlib
    pandas
