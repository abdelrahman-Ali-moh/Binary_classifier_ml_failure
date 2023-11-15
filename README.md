# Machine Learning Failure: Linear Regression Model
# Overview
This repository documents a machine learning project that attempted to utilize a linear regression model but ultimately faced significant challenges and limitations leading to suboptimal performance. Understanding and learning from such failures is an essential part of the data science and machine learning process.
# Problem Statement
The goal of this project was to predict targetes variable using a linear regression model. The dataset Provide about (Product ID ,Type,Air temperature [K] ,Process temperature [K],Rotational speed [rpm],Torque [Nm],Tool wear [min] )
Machine failure was chosen with the assumption that a linear relationship exists between the features and the target variable.
# Methodology
# Data Preprocessing
* Data Cleaning: The initial dataset required cleaning due to clear missing values.
Feature Engineering: selected columns after correlation data to know specific columns to trained it.
# Model Training
Linear Regression Model: The choice of a linear regression model was based on the assumption that a linear relationship exists between the features and the target variable.
# Sample code for linear regression
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train, y_train)
