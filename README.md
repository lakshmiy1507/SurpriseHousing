# Surprise Housing Case Study
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  - The company is looking at prospective properties to buy to enter the market. The company is looking at a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
  - They have contracted a consulting company to understand the factors which significantly affect the price of the house.
- What is the business problem that your project is trying to solve?
  - Which variables are significant in predicting the price of a house
  - How well those variables describe the price of a house.
  
- What is the dataset that is being used?
  - Fictitious Australian House sample dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The variables significant in predicting the price of a house are
  - GrLivArea - Demand increases with years
  - OverallQual - With increase in Temparature, the demand increases. 
  - GarageCars  - During snow, demand is less, where as clear weather has high demand
- R2 square for train dataset is 0.841 where as for test dataset is 0.805
- Residuals follow a normal distribution with mean centered around zero.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy, pandas
- matplotlib, seaborn-0.13.2
- datetime
- sklearn
- statsmodel
