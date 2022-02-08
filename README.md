# Assignment - Advanced Regression
## Assignment Part-I
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
>The company wants to know:
    -Which variables are significant in predicting the price of a house, and
    -How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
    -Which variables are significant in predicting the price of a house, and
    -How well those variables describe the price of a house.
- The data is provided in the CSV file.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 5 Variables which are most important in the model are:
    - GrLivArea (Above grade (ground) living area in square feet).
    - OverallQual_VG (Rates the overall material and finish of the house: Very Good).
    - OverallQual_EX (Rates the overall material and finish of the house: Excellent).
    - GarageCars (Size of garage in car capacity),
    - FullBath (Full bathrooms above grade).
- Optimal value of alpha for Ridge Regression: "8.0".
- Optimal value of alpha for Lasso Regression: "0.0004".

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- matplotlib
- seaborn
- pandas
- numpy
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project is given by UpGrad during PG Program in ML & AI.


## Contact
Created by [@githubusername] & [@SanketRBhave] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->