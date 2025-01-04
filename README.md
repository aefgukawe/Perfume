# Perfume Dataset: Exploratory Data Analysis and Predictive Modeling
In this Data science project, I tried to create a Jupyter notebook for data scraping, EDA, feature engineering, and prediction models for some of the most popular perfumes in 2024. The main objective of this project was to explore common characteristics of trending perfumes and leverage these insights to create a personalized recommendation system. 

## Project Highlights:
1. Data Acquisition:
- Conducted automated web scraping to compile a comprehensive dataset of perfumes, including details such as brands, names, inks, notes, longevity, ratings, years, categories, and gender preferences.
2. Data Cleaning + Feature Engineer:
- Handled missing data, normalized numeric variables, and encoded categorical attributes for model readiness.
- Designed features needed that are not readily available in the website
3. Exploratory Data Analysis (EDA):
- Performed a detailed exploratory analysis to uncover the dataset's trends, correlations, and distribution patterns.
- Visualized key insights such as the most frequently used fragrance notes for each gender, the relationship between gender and perfume category, and the breakdown of perfumes by gender and brands.
4. Predictive Modeling:
- Developed and compared multiple regression models to predict attributes like perfume longevity and gender preference. Models included:
  - Multiple Linear Regression
  - Decision Trees
  - Random Forests (with and without wrapper method for feature selection)
  - Gradient Boosting Models
- Evaluate model performance using appropriate metrics such as accuracy rate for classification tasks, Mean Squared Error (MSE) for regression analysis, and feature importance scores to assess the contribution of individual predictors.
5. Recommendation System:
- Built a K-Nearest Neighbors (KNN) recommendation system to suggest perfumes tailored to individual user preferences. Recommendations were based on attributes like what notes user preferred or what their current favorite perfume was.

## Significance and Applications:
This project provides actionable insights for perfume enthusiasts and industry professionals. Users can benefit from tailored recommendations, while brands can leverage data-driven findings to refine product development and marketing strategies. The combination of data science techniques and practical application ensures a comprehensive understanding of current perfume trends and their underlying drivers.
