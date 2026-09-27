# Airline Sentiment Analytics

Python NLP project that analyzes airline customer tweets and identifies recurring themes using TF-IDF and Non-Negative Matrix Factorization (NMF).

Developed for CS356: Foundations of Big Data Analytics.

## Overview

The application processes 14,640 airline-related tweets, transforms unstructured text into numerical TF-IDF features, and applies NMF topic modeling to identify common themes.

Each tweet is assigned a dominant theme, and the analyzed dataset is exported to a new CSV file.

## Key Features

- Processes 14,640 airline tweets
- Cleans records with missing text
- Converts text into up to 1,000 TF-IDF features
- Applies NMF to identify 5 recurring themes
- Displays the 10 most representative terms for each theme
- Assigns a dominant theme to each tweet
- Exports analyzed results to CSV

## Technologies

- Python
- pandas
- scikit-learn
- TF-IDF
- Non-Negative Matrix Factorization (NMF)
- Git / GitHub

## Running the Project

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the application

```bash
python airline_sentiment.py
```

## Output

The program:

- Displays the 10 most representative terms for each of the 5 discovered themes
- Assigns a dominant theme to each tweet
- Exports the analyzed dataset to a new CSV file

The generated output file is:

```text
Airline_Sentiment_With_Themes.csv
```

## Dataset

This project uses the Twitter US Airline Sentiment dataset from Kaggle.

The dataset contains airline-related tweets along with sentiment labels and supporting metadata.

## Project Structure

```text
Airline-Sentiment-Analytics/
├── .gitignore
├── README.md
├── Tweets.csv
├── airline_sentiment.py
└── requirements.txt
```
