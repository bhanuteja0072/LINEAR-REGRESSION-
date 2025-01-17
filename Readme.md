# Lending Club Case Study
> The goal is to predict noof rentals a bike rental company would do on a given day by considering various factors like season , temeperature , humidity etc.The predictions are to be done using a linear regression model . This is basically a regression problem




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information
- The assigment is about predicting the noof bike rentals a company would do on a particular day
- The model used to predict the target variable is regression model , the metric used to measure goodness of fit is r-squared
- The p-values of coefficients were taken into consideration before eliminating any features . 
- MinMax Scaler was used for scaling numerical data
- F-Statistic of the model was also taken it consideration , to verify the variance explained by the model
- RFE and Backward Feature Elimination , both these techniques were used to experiment 

## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.24.2
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- re - version 2.2.1
- Scikit-learn 1.1
- SciPy 1.11.3
- statsmodel 0.14.0



## Conclusions
- The 3 most important fetures to the model are temp,weathersit_3 and yr
- There is highest loss in r2-square if yr is removed , r2-score reduces approx by 0.3 
- temp has the highest correlation with the target column 
- more bikes were rented in the year 2019 than in the year 2018
- An r2-score of 0.78 was observed with Backward Feature Elimination and an r2-score of 0.77 was observed with RFE.






