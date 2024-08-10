 # Sentiment Analysis Project

## Overview

This project performs sentiment analysis on tweets using the `nltk` library's `SentimentIntensityAnalyzer`. The script reads a CSV file of tweets, processes each tweet to determine its sentiment (positive, negative, or neutral), and then aggregates the results.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis.git
   cd sentiment-analysis
2. Install the required Python packages:
   ```bash
   pip install pandas nltk pyspark
3. Download the nltk VADER lexicon:
   ```bash
   import nltk
   nltk.download('vader_lexicon')
## Usage
1. Place your CSV file containing tweets (sentiment_tweets3.csv) in the project directory.
2. Run the notebook:
   ```bash
   jupyter notebook SENTIMENTAL_ANALYSIS.ipynb
The script will output the sentiment counts (positive, negative, neutral) based on the analysis.
## What the Script Does
- Imports libraries (pandas, nltk) and downloads the necessary lexicon.
- Defines functions to analyze sentiment and aggregate results.
- Reads a CSV file containing tweets.
- Analyzes the sentiment of each tweet.
- Aggregates and prints the sentiment counts.

