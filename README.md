# Natural-Language-proccessing-




# Summary

- Reading data

- Exploratory Data Analysis

- Tokenization and Features Engineering

- XGBoost baseline model



# Problem

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies.




# Solution

I used Natural Language Proccessing to predict which Tweets are about real disasters and which ones are not.




# Data

We are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

Each sample in the train and test set has the following information:

- The text of a tweet
- A keyword from that tweet (although this may be blank!)
- The location the tweet was sent from (may also be blank)




# Modeling


- Define a stratified K-Fold to preserve percentage of each target class

- Use RandomizedSearchCV for finding best hyperparameters

- Fit XGBoost baseline model


# Result

![ana20](https://user-images.githubusercontent.com/33470542/81594997-c270cc00-938f-11ea-9aec-00224202ff57.png)
