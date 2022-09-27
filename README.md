# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market. It is required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
A company wants to enter Australian market. So it is looking at prospective properties to buy to enter the market. It is required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
- The model is trained using Ridge & Lasso regression to reduce complexity of model
- Lasso performs better when there are too many independent variables as it does automatic feature selection
- The ccuracy obtained is around 88 % for training & test dataset 
- The 5 most important predictor variables according to ridge are - 
    OverallQual_Qual_Excellant             
    GrLivArea                              
    FullBath_3                             
    OverallQual_Qual_VExcellant            
    GarageCars_3  
- The 5 most important predictor variables according to lasso are - 
    RoofMatl_CompShg                       
    GrLivArea                              
    RoofMatl_WdShngl                       
    RoofMatl_Tar&Grv                       
    OverallQual_Qual_Excellant  

## Technologies Used
- numpy
- pandas
- plotly
- matplotlib
- seaborn
- scikit-learn

## Contact
Created by AparnaBindage - feel free to contact me!