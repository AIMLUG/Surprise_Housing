# Surprise_Housing - Advanced Linear Regression Analysis
Build a multiple linear regression model for the prediction of demand for shared bikes.

This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Performed the EDA analysis, Data Visualization on continous numaric and categorical variables to understand the distribution of data
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

-- Business Goal 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

R-Squared values<br><br>
  Training: Ridge: 0.9405173869929192 <br>
  Test : Ridge: 0.8840439738982031<br><br>

  Training: Lasso: 0.9239577143380369<br>
  Test : Lasso: 0.8904134828285906<br><br>

  Optimal Lasso lambda value: {'alpha': 6.0}<br>
  Optimal Lasso lambda value: {'alpha': 0.001}<br><br>
  
- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set.

- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas, Numpy
- Seaborn
- matplotlib
- scikit learn
- Ridge
- Lasso

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@kunkasurendra] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
