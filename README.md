# Airline Sentiment Analysis

## Overview
This project analyzes tweets related to airlines to determine public sentiment—positive, negative, or neutral—using natural language processing (NLP) techniques. It provides insights into customer opinions and highlights areas for service improvement.

## Dataset
The dataset is publicly available on [Kaggle](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) and contains airline-related tweets with sentiment labels.  

**Key columns:**  
- `tweet_id`: Unique identifier for each tweet  
- `airline_sentiment`: Sentiment label (positive, negative, neutral)  
- `text`: Content of the tweet  
- `airline`: Airline mentioned in the tweet  

## Objectives
- Classify tweets as positive, negative, or neutral  
- Identify trends and patterns in airline sentiment  
- Visualize sentiment distribution across airlines  
- Demonstrate NLP preprocessing and machine learning classification  

## Approach
1. **Data Cleaning & Preprocessing**  
   - Remove null values, duplicates, and irrelevant characters  
   - Tokenization, lowercasing, and stopword removal  
   - Vectorization using TF-IDF  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize sentiment distribution  
   - Identify airline-specific trends  
   - Generate word clouds for positive and negative tweets  

3. **Modeling**  
   - Train models like Random Forest Classifier and XGB Classifier
   - Evaluate using accuracy, precision, recall, and F1-score  

4. **Visualization & Insights**  
   - Sentiment distribution across airlines  
   - Common words in positive and negative tweets  

## Tools & Libraries  
- Pandas, NumPy  
- Matplotlib, Seaborn, WordCloud  
- Scikit-learn  
- NLTK  

## Results
- Best performing model: **[XGB Classfier]**  
- Accuracy: **[78%]**  
- Key Insights:  
  - Certain airlines receive consistently positive or negative feedback  
  - Common positive/negative keywords identified  

## Future Work
- Deploy a real-time sentiment analysis dashboard  
- Analyze sentiment trends over time  
- Use deep learning models (LSTM, BERT) for better performance  
