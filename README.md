# Bay Area House Price Prediction 
# Introduction
This project aims to tackle the challenge of predicting house prices in the Bay Area, leveraging advanced data mining techniques. Utilizing data scraped from Zillow's API, we've developed a machine learning model that factors in a comprehensive set of property attributes to forecast accurate housing prices.

# Motivation
The escalating housing costs in the Bay Area significantly impact the community's quality of life. Our project seeks to provide data-driven solutions to optimize housing affordability, thereby enhancing the well-being of our community.

# Community Contribution
Our predictions serve multiple stakeholders:

Real Estate Transactions: Aids in fair price negotiation for buyers and sellers.

City Planning: Offers insights for strategic development and affordable housing initiatives.

Financial Institutions: Assists in property valuation for lending and refinancing.

Policy Making: Informs decisions related to housing taxes and regulations.

# Project Flow

Data Collection: Scraping Zillow's website using API.

Data Cleaning and Preprocessing: Rigorous cleaning and feature engineering.

Exploratory Data Analysis: Understanding data distribution and correlations.

Model Development: Building and training predictive models.

Evaluation and Tuning: Assessing model performance and optimizing parameters.

# Data Collection

Source: Zillow Website through Zillow APIs.

Features: Property details including location, size, type, and historical sale prices.

Format: Data initially obtained in JSON, converted to a comprehensive dataframe for analysis.

Data Cleaning & Transformations

Handled missing values and standardized data formats.

Dropped irrelevant columns and filtered out non-contributing records.

Engineered new features such as 'Age_inYears' for improved model accuracy.

Applied normalization and one-hot encoding for numerical and categorical data, respectively.

# Exploratory Data Analysis (EDA)

Analyzed distribution of target variables and property features.

Created interactive visualizations to explore geographical data distribution.

Examined correlations between housing features to identify key predictors.

# Model Building & Training

Employed various machine learning algorithms, including:

K-Nearest Neighbors (KNN)

Random Forest Regressor

CatBoost Regressor

LightGBM

XGBoost Regressor

# Model Evaluation

Utilized metrics such as MAE, MSE, and RMSE for model comparison.

Conducted hyperparameter tuning to optimize model performance.

Identified XGBoost Regressor as the best performing model based on evaluation metrics.

# Conclusion
Our in-depth analysis of the Bay Area real estate market has provided valuable insights into property price predictions and market trends. By employing a range of machine learning models and fine-tuning their parameters, we've achieved robust predictions that contribute significantly to understanding factors influencing property values.

# Contact Information
For inquiries or further discussion, feel free to contact:

Rithwik Maramraju: rithwik.maramraju@sjsu.edu
