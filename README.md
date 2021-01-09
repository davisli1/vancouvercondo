# Vancouver Condo Pricing Project

## Purpose: I want to invest in a condo in Vancouver, so I want to create a Machine Learning model to help me price properties

## Process:
1. Parse Data from Website
    - Parsed 550 results for Condos listings in Vancouver from rew.ca
    - Data includes: price, address, property type, region, city, bedrooms, bathrooms, sqft
2. Clean Data: 
    - Cleaned up some lines and stored into data_clean
3. Visualization of data:
    - Visualized data through boxplots, regressions and correlation heatmaps
    - SQFT had the highest correlation for price, second was # of bathrooms and third was # of bedrooms
4. Build machine learning model
    - Used LinearRegression model with variables of sqft, bedrooms and bathrooms, returning an accuracy of 77% through 4 cross validations
    - Converted regions (categorical) into numerical values to be used, alongside the other variables
    - Used GradientBoostingRegression and cross validated 5 times, returning an accuracy of 84%

## Result: The final machine learning model using GradientBoostingRegression returned an accuracy of 84% 

## Next up:
    - Increase Data Sample and add in variables such as year built and possibly area analysis (near skytrain, mall.etc)


 