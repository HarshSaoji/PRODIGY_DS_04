# Sentiment Analysis and Visualization of Social Media Data

## Overview

This repository contains the solution for analyzing and visualizing sentiment patterns in social media data as part of Task 4 during my internship at Prodigy Infotech. The objective was to understand public opinion and attitudes towards specific topics or brands by conducting sentiment analysis on social media data.

## Dataset

- **Dataset Name:** Twitter Sentiment Analysis Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- **Description:** The dataset consists of Twitter data with sentiment labels assigned to each tweet. It includes information about entities (brands, products, etc.), along with sentiment scores such as positive, negative, neutral, and mixed.

## Solution Overview

1. **Data Reading and Cleaning:**
   - Loaded the training and validation datasets into pandas DataFrames.
   - Cleaned the data by handling missing values and standardizing sentiment labels.

2. **Exploratory Data Analysis (EDA):**
   - Explored the distribution of sentiment labels in the dataset.
   - Analyzed sentiment patterns by entity, identifying top entities and their corresponding sentiment distributions.
   - Visualized sentiment distribution using pie charts and bar plots.

3. **Model Building:**
   - Utilized Natural Language Processing (NLP) techniques for text preprocessing and feature extraction.
   - Implemented a Multinomial Naive Bayes classifier for sentiment prediction.
   - Trained the model on the training data and evaluated its performance on the validation data.

4. **Results and Insights:**
   - Successfully built a sentiment analysis model with an accuracy score of 84.6% on the validation data.
   - Generated insights into public sentiment towards specific entities, identifying trends and sentiment shifts.

## Usage

1. **Data Preparation:**
   - Ensure you have the `twitter_training.csv` and `twitter_validation.csv` files in the repository.

2. **Model Training and Evaluation:**
   - Run the provided Python script to load the data, preprocess it, train the model, and evaluate its performance.

3. **Visualization:**
   - Customize the visualization code to explore sentiment patterns further or generate additional insights.

4. **Future Work:**
   - Extend the analysis to include more sophisticated NLP techniques or explore other machine learning algorithms for sentiment analysis.
   - Incorporate real-time data scraping to analyze current public sentiment trends.

## Conclusion

This project enhanced my skills in sentiment analysis, data visualization, and deriving insights from social media data. The findings from this analysis can be valuable for businesses, marketers, or researchers aiming to understand and leverage public sentiment towards specific topics or brands.


