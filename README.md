# Sentiment Analysis of US Election 2020 using RNN

## Introduction
This project involves sentiment analysis of tweets related to the US Election, focusing on the candidates Donald Trump and Joe Biden. The analysis utilizes Recurrent Neural Networks (RNNs) to classify the sentiment of tweets.

## Dataset
The dataset consists of tweets collected during the period leading up to the US Election. Two separate datasets were used, one for tweets related to Donald Trump (`hashtag_donaldtrump.csv`) and another for Joe Biden (`hashtag_joebiden.csv`). Both datasets include information such as tweet content, likes, retweet count, user details, and geographical information.

## Data Exploration
The datasets were loaded into Pandas DataFrames, and basic exploration was conducted to understand the structure and content.

## Data Preprocessing
Data cleaning and preprocessing were performed to prepare the text data for sentiment analysis. This involved removing unnecessary characters, converting text to lowercase, and lemmatization.

## Sentiment Analysis
Sentiment analysis was conducted using the TextBlob library. The sentiment scores (polarity and subjectivity) were calculated for each tweet, and the sentiment was categorized as positive, neutral, or negative.

## Exploratory Data Analysis (EDA)
EDA was performed to visualize tweet statistics, compare likes, and analyze tweet distribution across countries.

## Conclusion
This project provides insights into the sentiment of tweets related to the US Election for the candidates Donald Trump and Joe Biden. The analysis includes data preprocessing, sentiment analysis, and exploratory data analysis. The visualizations help understand the distribution of tweets and sentiments across different countries.

Feel free to explore the complete analysis in the Jupyter Notebook (`Sentiment_Analysis_US_Election.ipynb`).
