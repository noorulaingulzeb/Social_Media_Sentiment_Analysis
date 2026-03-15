# Social Media Sentiment Analysis

This project implements a Natural Language Processing (NLP) model to classify social media posts into Positive, Neutral, or Negative sentiments.

## Features
- Preprocessing: label mapping, balancing, removing empty posts
- TF-IDF vectorization of text
- Naive Bayes classification
- Custom predictions possible
- Achieved ~72% accuracy

## Dataset
- Social media posts CSV (~74,000 rows)
- Balanced dataset (~55,000 rows used for training)
- Custom test posts can be added for predictions

## How to Use
1. Upload your CSV dataset to Google Drive
2. Open `sentiment_analysis.ipynb` in Colab
3. Run all cells
4. Test your own social media posts in the "Custom Predictions" section

## Technologies
Python, Pandas, Scikit-Learn, NumPy
