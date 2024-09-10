
---

# News Sentiment Analysis

This project involves sentiment analysis of news articles. Using a dataset of news articles with sentiment labels, the project performs data exploration, preprocessing, visualization, and classification using various machine learning models.


## Project Overview

1. **Data Import & EDA**
   - Loaded the dataset and performed basic exploratory data analysis (EDA).
   - Checked for missing values and duplicates.

2. **Data Transformation**
   - Cleaned the data by removing missing values and duplicates.
   - Preprocessed the text data by removing unnecessary characters and links.

3. **Data Visualization**
   - Created visualizations to explore sentiment distribution, news type distribution, and text length distribution using seaborn and plotly.

4. **Modeling**
   - Implemented and evaluated the following machine learning models:
     - Logistic Regression
     - Random Forest
     - XGBoost Classifier
   - Used TF-IDF vectorization for text data and performed model training and evaluation.

5. **Evaluation**

   The following table summarizes the performance metrics of each model:

   | Model               | Accuracy | 
   |---------------------|----------|
   | Random Forest       | 82.79%   | 
   | Logistic Regression | 79.05%   | 
   | XGBoost Classifier  | 84.79%   | 

   - **XGBoost Classifier** achieved the highest accuracy (84.79%).


```

