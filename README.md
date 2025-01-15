# Bostan-house-price-prediction

# Description

This project focuses on developing an estimate of house prices in Bostan using a dataset from Kaggle,Bostan-house-price-prediction. The model is designed to predict the house price using multiple input variables. 
# EXPLORATORY DATA ANALYSIS

performed the EDA process to clead the data and get rid of unusable informatioin. I converted the data from object type to numeric type.

Then IN order to see the coorelation between different columns, I plot the coorelation matric and droped down the highly coorelated matrics.


# Model
**Model Traning and test**
for traning model first I have to split the dataset using train_test_split function.
Then I used the XGBoost Regressor Model to train on dataset. I use .fit()fuction to train it.

After traning model on traning dataset I then test the MODEL on teat dataset and for that I used .predict() function


# Model Evaluation
For Evalution perpose I used R squred error and mean absolute error.

R squared error : 0.9999980039471451
Mean absolute error : 0.0091330346494618
