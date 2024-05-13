# Twitter Sentiment Analysis

## Introduction

This project aims to analyze tweets related to the 2012 U.S. presidential elections, focusing on Barack Obama and Mitt Romney. It builds a sentiment classification pipeline using machine learning techniques to classify tweets as positive, negative or neutral.

## Techniques

### Data Preprocessing

- Removed URLs, usernames, HTML tags, and punctuation.
- Eliminated stop words while retaining negative conjunctions.
- Converted words with apostrophes to their base forms.
- Dropped unnecessary columns like date, time, and mixed opinion values.
- Tokenization to reduce feature space and enhance word significance.

## Model Selection
Naive Bayes' and Roberta were used to classify the tweets.


