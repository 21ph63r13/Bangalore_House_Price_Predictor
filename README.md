# Bangalore House Price Predictor

## Project Overview

The Bangalore House Price Predictor is a machine learning-based web application that predicts house prices based on various features such as location, square footage, number of bedrooms, and bathrooms.

This project is deployed on Render and allows users to estimate house prices interactively.

## Dataset

The dataset used for this project contains 6798 entries with the following features:

location: The locality of the house in Bangalore.

total_sqft: Total area of the house in square feet.

bath: Number of bathrooms.

bhk: Number of bedrooms, halls, and kitchens.

price: The house price in lakhs (target variable).

## Technologies Used

Python (Machine Learning and Backend)

Flask (Web Application Framework)

Scikit-learn (Machine Learning Model - Ridge Regression)

Pandas & NumPy (Data Processing)

Matplotlib & Seaborn (Data Visualization)

Render (Deployment)

Machine Learning Pipeline

Data Cleaning & Preprocessing:

Handled missing values and outliers.

Converted categorical locations into numerical representations using One-Hot Encoding.

Standardized numerical features.

Feature Engineering:

Removed redundant or highly correlated features.

Derived new features such as price per square foot.

## Model Selection & Training:

Used Ridge Regression for predicting house prices.

Trained the model on cleaned data and evaluated performance.

Model Evaluation:

Used metrics like Mean Absolute Error (MAE) and R² Score to assess accuracy.

Deployment:

Created a Flask API to serve the model.

Deployed the application on Render.
