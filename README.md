# Twitter Sentiment Analysis 📊💬

Welcome to the **Twitter Sentiment Analysis** project! This project aims to analyze the sentiment of tweets using machine learning techniques. Below, you'll find a comprehensive overview of the project, including data transformation, visualization, and model building. Let's dive in! 🚀

## Table of Contents
1. **Project Overview**
2. **Data Transformation**
3. **Data Visualization**
4. **Model Building**
5. **Performance Evaluation**

## Project Overview 📝
The goal of this project is to classify tweets into different sentiment categories such as Positive, Negative, Neutral, and Irrelevant. The process involves data preprocessing, feature extraction, and applying machine learning models to predict the sentiment of tweets.

## Data Transformation 🔄
In this phase, we perform various preprocessing steps to clean and prepare the data for analysis. This includes:
- Loading datasets 📂
- Converting text to lowercase 🔠
- Removing special characters using regular expressions 🧹
- Tokenizing text for feature extraction ✂️

## Data Visualization 📈
Visualization helps in understanding the distribution of tweets across different sentiment categories. We use WordClouds and bar plots for this purpose:
- **WordClouds**: To visualize the most frequent words in Positive, Negative, Neutral, and Irrelevant tweets 🌧️☀️
- **Bar Plots**: To show the distribution of tweets per category and information type 📊

## Model Building 🛠️
We build and evaluate two models using the Bag of Words technique:
1. **Logistic Regression with unigram features**:
   - Train-test split of the dataset
   - Transformation of text into numerical features using CountVectorizer
   - Training and predicting using Logistic Regression
   - Achieved an accuracy of 90% on the test dataset and 98% on the validation data

2. **Logistic Regression with 4-gram features**:
   - Enhanced feature extraction using 4-grams
   - Training and predicting with the updated feature set
   - Superior performance compared to the unigram model

## Performance Evaluation 🎯
We evaluate the models based on their accuracy scores to determine how well they classify the sentiments. The final model with 4-gram features demonstrates higher accuracy, making it the preferred choice for this analysis.


