# Sentiment Analysis Project

## Overview

This project focuses on sentiment analysis of tweets engagement metrics using machine learning techniques. The goal is to classify tweets into three categories: Negative, Neutral, and Positive. The project involves exploratory data analysis (EDA), handling missing values, visualizations, correlation analysis, and building a classification model.

### Data Exploration

- Checked data head, info, describe, shape, columns, missing values, and null values.
- Explored each column using visualizations with matplotlib and seaborn.
- Performed correlation analysis to understand relationships between different features.

### Preprocessing

- Handled missing values and dropped null values.
- Conducted text preprocessing on 'text' column, including lemmatization, stemming, and removing stop words.
- Engineered features to enhance model performance.

### Classification Model

- Built a classification model using a pipeline with TF-IDF and RandomForest.
- Achieved a training accuracy of 91%.
- Evaluated the model using a test dataset and printed the classification report.

## Results

The classification model demonstrated strong performance with a training accuracy of 91%. The evaluation on an unseen dataset is presented in the classification report within the Jupyter notebook.

## Disclaimer

This project is for educational purposes only and should not be used for real-world financial decisions.

