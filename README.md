# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* Problem Statement
* Conclusions
* Technologies Used
* Acknowledgements

<!-- ### Business Objectives
The company wants to know:

- Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house. -->

## General Information
- Provide general information about your project here.
### Exploratory Data Analysis
   Data Understanding
   Data Cleaning
   Univariate Analysis
   Bivariate Analysis
   Dummay variable creation for converting catogorical variables into numerical variables
   Splitting data into Train and test sets
   Building Linear Model 
   Building Ridge and Lasso Regression model
   comparing the results

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Variables that are highly correlated with Sale Price are : OverallQual,GrLivArea, GarageArea, TotBsmtSF, 1stFlrSF,TotalRmsAbvGrd,FullBath and YearBuilt
- GarageArea and GarageCars are highly correlated with a correlation of 0.88
- TotRmsAbvGrd and GrLivArea are correlated to each other with a correlation of 0.83
- 1stFlrSF and TotalBsmtSF are highly correlated with a correlation of 0.82
- The higher the coefficient the important the predictor hence these variables are impacting the Housing SalePrice more
- alpha value for Ridge is 5 and for Lasso it is 0.0001
- R2-Score value of Ridge is better than Lasso 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 1.3.4
- numpy - 1.20.3
- matplotlib - 3.4.3
- seaborn - 0.11.2
- SKlearn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- train  Dataset
- Data Dictonary


## Contact
Created by [@Neelima123] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->