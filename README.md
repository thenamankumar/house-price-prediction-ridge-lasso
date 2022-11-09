# House Price Prediction
> This project is part of the Linear Regression Assignment Module 2 under course 3 Machine Learning 1

**Problem Statement**

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. The requirement is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [Jupiter Notebook](https://github.com/thenamankumar/house-price-prediction-ridge-lasso/blob/main/notebook.ipynb)
* [Subjective Questions](https://github.com/thenamankumar/house-price-prediction-ridge-lasso/blob/main/Subjective%20Questions.pdf)
* [Dataset](https://github.com/thenamankumar/house-price-prediction-ridge-lasso/blob/main/data.csv)
* [Definitions](https://github.com/thenamankumar/house-price-prediction-ridge-lasso/blob/main/description.txt)

## Conclusions
After building and comparing multiple models we can now conclude that the Lasso Regression model gives us the best results. 40 features are considered by this model for sale price prediction which is a significant reduction from the 293 columns provided originally.

- r-square for train data set is 0.821
- r-square for test data set is 0.806
- top 10 features used for prediction are:
    - GrLivArea
    - OverallQual
    - GarageCars
    - Neighborhood_NoRidge
    - BsmtExposure_Gd
    - Neighborhood_NridgHt
    - SaleType_New
    - BsmtFinType1_GLQ
    - TotRmsAbvGrd
    - Condition1_Norm
