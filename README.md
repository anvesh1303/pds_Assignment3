# PDS Assignment 3

This repository contains code and data for analyzing and visualizing the sentiments expressed in tweets related to the coronavirus pandemic.

## Dataset

The dataset consists of the following columns:

- UserName: An integer identifier for the user
- ScreenName: An integer identifier for the user's screen name
- Location: The location of the user
- TweetAt: The date of the tweet
- OriginalTweet: The text of the tweet
- Sentiment: The sentiment of the tweet (e.g., Extremely Negative, Negative, Positive, etc.)


## Data Processing and Analysis

The R script in this repository performs the following steps:

1. Read the raw data from a CSV file
2. Preprocess the text in the "OriginalTweet" column (e.g., remove URLs, mentions, non-alphanumeric characters, and convert to lowercase)
3. Save the cleaned data to a new CSV file
4. Tokenize the text
5. Remove stopwords
6. Count word frequencies
7. Create a word cloud visualization

The results of these steps are saved in the following files:

- Cleaned_Carona_NLP_test.csv: Cleaned data
- tokens.csv: Tokenized text
- tokens_no_stopwords.csv: Tokenized text with stopwords removed
- word_freq.csv: Word frequencies
- wordcloud.png: Word cloud visualization

## How to Run

To run the R script, you need to have R and the required packages installed. Then, execute the script from the command line or from an R environment.

Required packages:

- tidytext
- dplyr
- ggplot2
- tm
- wordcloud


