# Kaggle Diamonds Competition
![Alt text](images/diamonds_image.jpg)

## Overview
The aim of this competition is to predict the prize of diamonds based on their characteristics like weight, color, quality, volume, etc.

## Structure
The project has three folders:
- **Input**: contains the riginal datasets and the datasets obtain from the cleaning of data.
- **Output**: folder with the sbmisions in csv format
- **Main**: jupyter notebook files with the process followed to obtain the output
- **Images**

## Steps followed
1. **Cleaning** of the dataset: see the correlation beteen the different variables and drop different ones to see how it affect the model, make the dummies of the categorical data.

standardize 

2. Divide the data in the train dataset into train and test.

3. Train the following **models** with this data and check the models with the r2 score and the RMSE as well as optimize several models using GridSearchCV
- Linear Regression
- K Neighbors Regressor
- Random Forest
- Decision Tree
- Epsilon-Support Vector Regression
- Elastic Net
- Gradient Boosting Regressor

4. Train the model with the Kaggle predict dataset and predict the test values.




