***Phase 2 Project***

***Content***
#kc_house_data.csv - King's County Housing Dataset 2014-2015
#Phase 2 Project.ipynb -Jupyter notebook with code
#Presentation - Business Non Technical Presentation

***Summary***
The King's County Housing dataset provides several variables that can be used to create a prediction model. The prediction model used was a multivariate linear regression. Log transformations were used for continuous variables. One hot encoding was performed for categorical variables.
The final result of the multivariate linear regression was 0.634.


***Conclusion***
#The final model has an adjusted R-squared value of 0.634. 
#With adjustments to the categorical variables and the continuous variables we can more accurately predict our dependent variable 'price'.
#For the continuous variables, we applied log transformations to the continuous data for them to appear more normal. 
#Normalization was also applied to reduce the effect of outliers and reduce the values to be between 0-1. 
#To handle categorical variables we used one hot encoding.
#The three best predictors for the sale price of a house are square footage of the living area, number of bathrooms/bedrooms and condition of the house

***Business Recommendations***
#To increase the sale price of a house, we can;
#1. Increase the amount of bathrooms 
#2. Increase the number of bedrooms of the property 
#3. Renovate the property to help improve the condition of the house. 
