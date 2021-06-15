# seattle_airbnb_price
How to Predict Seattle Airbnb Listing Price using Machine Learning with Python

This project aims to answer the following questions:
1. Does location e.g. neighbourhood affect listing price?
2. Does the type of property and room affect listing price?
3. What are the top 5 factors influencing the listing price? To be answered using a machine learning model, Random Forests.

The project starts with exploring and cleaning the Seattle Airbnb dataset downloaded from Kaggle. 

The cleaning process involves removing columns that do not contribute to predict listing price, dealing with missing values, converting the price variable from string to float and others. 

Upon cleaning the dataset, we answer question 1 and 2. 

Then, we train a Random Forest Regressor using the cleaned dataset and find out the top 5 factors that influenced the listing price. 

My Medium blog post can be found in the link below:

https://vincent-chw.medium.com/how-to-predict-seattle-airbnb-listing-price-using-machine-learning-with-python-e34a68449f0a

Files in repository:
Python project file - Main project file consists of exploring the dataset, cleaning the dataset, find answers to the questions above, and train a Machine Learning model to predict the listing price. 

seattle_listings.csv - The Seattle Airbnb Listing dataset downloaded from Kaggle. You can get the dataset from the link below as well. 

https://www.kaggle.com/airbnb/seattle


Libraries used:
Numpy
Pandas
Matplotlib
Random Forest Regressor
R2 Score

Version Control:
Python version = 3.7.3
Numpy = 1.18.5
Pandas = 0.25.3
