# Kings County House Price Prediction
# BUSINESS UNDERSTANDING

## Overview

Cherie real estate agency is a housing stakeholder that gives advice to homeowners so that they can buy and/or sell home.
The agency want to help homeowners to be able to predict the current and future prices of their houses depending on different fearures.

Build a linear regression model that will help the stakeholder to predict prices based on features like Square footage of living space in the home, Square footage of the lot, Number of floors (levels) in house, codition of the house, presence of a waterfront,number of bedrooms and bathrooms,grade of the house and the year built.

Also the model will help us know which featurs increases or decreases the price of the houses.

# DATA UNDERSTANDING

The data used is from kc_house_data.csv.

The data has 21597 homes with 21 features of the house.

The features include:
- Sale price (prediction target)
- Number of bedrooms
- Number of bathrooms
- Square footage of living space in the home
- Square footage of the lot
- Number of floors (levels) in house
- Whether the house is on a waterfront
- How good the overall condition of the house is. Related to maintenance of house.
- Overall grade of the house. Related to the construction and design of the house.
- yr_built - Year when house was built

The price is our target  variable.

# Modelling

I created models that would help in predicting the prices of the homes.
The first model was a simple linear regression model. Here the most correlating feature with the price was used. This model had an adjusted r_squared of 50% .

I created a multiple linear regression model to check if the accuracy would improve.

The first model had an adjusted r_squared of 50%.

The second one had an adjusted r_squared of 56%.

The third one had an adjusted r_squared of 68%.

I concluded that using the third model for predicting the price would be good.

# Conclusion
Some features present increases the price of the houses.

This features include: the condition of the house,number of bedrooms,number of floors and square foot of the living room leads to an increase in the price.

# LIMITATIONS
One of the limitation of the model is that it assumes that there is a linear relationship between the dependent and the independent variables

If there is any non-linear relationship between any independent variable and the independent variable, the model will perform poorly.
