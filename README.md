# Predicting-Price-for-AirBnB
Machine Learning, Regression Modeling, Data Cleaning, Exploratory Data Analysis

# Data Description:
Dataset comes from Kaggle's Inclass Prediction Competition, 2018 and can downloaded from https://www.kaggle.com/c/qbus6810-s1-18/overview.
Property prices are dependent on location and how close are they to the tourist attraction places. Based on location, we predict the price of AirBnB property using regression and RSME is the metric of evaluation. 

# Process:
* Perfrom feature engineering, data cleaning and Exploratory Data Analysis deem necessary.
* Identiify features that can predict price.
* Train and evaluate the model.

# Findings:
* "Price" is the target variable. "Price" and "accomodation" are dependent. A lot of low price properties accommodate only 1 person. Most of medium priced accomodates 3/4 persons. 
* High pricing follows strict policy for cancelling and flexible pricing houses demand only low pricing. Hence, cancellation policy is a criteria for predicting.
* High pricing follows strict policy for cancelling and flexible pricing houses demand only low pricing. Hence, cancellation policy is a criteria for predicting.
* This is a regression problem where I have used Random Forest to predict the pricing. Model scored an adjusted R Squared of 93%.
* RMSE error, the evaluation metric for this model is 22.85, which means our prediction price is $22 away from actual price.
