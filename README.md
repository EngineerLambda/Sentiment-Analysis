# **Sentiment Analysis of IMDb Movie Reviews**

## **Project Overview**

This project explores sentiment analysis of movie reviews in the IMDb dataset. It demonstrates:

- Text preprocessing techniques for cleaning and preparing reviews for analysis
- Feature extraction using TF-IDF Vectorizer to represent reviews as numerical vectors
- Machine learning model development with Logistic Regression for sentiment prediction
- Visualizing frequent words and model performance using WordCloud and confusion matrix

## **Key Steps**

1. **Data Loading and Exploration:**
    - Load the IMDb dataset.
    - Analyze the balance of positive and negative reviews.

2. **Text Preprocessing:**
    - Count words per review.
    - Encode sentiment labels as 0s and 1s.
    - Remove noise from text using regular expressions.
    - Stem words to reduce them to their base forms.

3. **Feature Extraction:**
    - Apply TF-IDF Vectorizer to create a numerical representation of reviews.

4. **Model Building:**
    - Train a Logistic Regression model for sentiment prediction.

5. **Evaluation and Visualization:**
    - Create a `sentiment_analysis` function to predict sentiment on new reviews.
    - Generate a WordCloud to visualize frequent words.
    - Construct a confusion matrix to evaluate model performance.
