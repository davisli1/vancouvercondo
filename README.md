This is my project for looking at Real Estate Data in Vancouver

Purpose: I want to invest in a condo in Vancouver, so I want to create a Machine Learning model to help me price properties

Process
1. Parse Data from Website
    - Parsed 550 results for Condos listings in Vancouver from rew.ca, also parsed 547 for all types of properties but didn't use
    - Data includes: price, address, property type, region, city, bedrooms, bathrooms, sqft
2. Clean Data: 
    - Cleaned up some lines and stored into data_clean
3. Visualization of data:
    - Visualized data through boxplots, regressions and correlation heatmaps. SQFT had the highest correlation for price, second was # - of bathrooms and third was # of bedrooms
4. Build ML linear regression model
    - Converted regions (categorical) into numerical values to be used. Used the sqft, property type, bedrooms, and bathroom variables
    - 75% data was for training, and other 25% was for testing
    - Cross validated 4 times 

Result: After cross validating the data 4 times, the ML model was on average 76% accurate

Next up:
    - Add in variables such as year built, land plot size, BC assessment price, and possibly area analysis (near skytrain, mall.etc)
    - Expand data to include more samples


 