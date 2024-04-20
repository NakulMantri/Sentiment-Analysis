# Sentiment-Analysis

## Overview
The project focuses on sentiment analysis of product reviews to provide insights for businesses. It employs a combination of rule-based heuristics and machine learning algorithms to analyze user sentiments and behaviors, helping businesses make informed decisions.

## Dependencies
- pandas
- numpy
- emoji
- nltk
- re
- string
- TextBlob
# Steps

## Data Preprocessing
1. **Load the dataset using pandas.**
2. **Check for and remove duplicate rows.**
3. **Handle missing values, if any.**

## Text Cleaning
1. **Define a function to clean reviews by removing special characters, stopwords, and applying lemmatization.**
2. **Clean each review in the dataset.**

## Dynamic Feature Extraction
1. **Define a function to extract dynamic features from reviews, such as noun phrases.**
2. **Extract dynamic features from the cleaned reviews.**

## Aspect-Based Sentiment Analysis
1. **Define a function to analyze the sentiment of reviews based on specific aspects.**
2. **Analyze the sentiment of each review for the extracted dynamic features.**

## Aggregate Ratings
1. **Calculate positive and negative counts for each dynamic feature.**
2. **Calculate the percentage of positive sentiments for each feature.**
3. **Scale the positive percentages to a rating scale (e.g., 5 stars).**




## Installation
Install the required dependencies using pip:
```bash
pip install pandas numpy emoji nltk TextBlob



