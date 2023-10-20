# Surprise Housing
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The objective is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The technical goal is to use Multiple Linear Regression to build a model to predict the key factors that affect the price of rentals from the given dataset. 
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

The assignment has two parts:
- Regression model to be built for the usecase
- Subjective questions to be answered


## Conclusions
- Lasso regression with alpha = 0.001 is best suited for this usecase. 
- The conclusion is arrived at by comparing the regression metrics R2-score, RSS and MSE values on test dataset.
- The top ten predictor variables have been identified.


## Technologies Used

### Data Manipulation Libraries
- Pandas
- Numpy
- missingno

### Data Visualization Libraries
- Matplotlib
- Seaborn

### Data Analysis and Modeling Libraries
- sklearn


## Contact
Created by [@jenifer2409] - feel free to contact me!