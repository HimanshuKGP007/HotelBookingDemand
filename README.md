# HotelBookingDemand

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HimanshuKGP007/HotelBookingDemand/HEAD)

## Project Description:

- Used Hotel Booking dataset to analyse different parameters which affect the decision making of the customer for booking a room in the hotel
- Performed Data Cleaning for performing the EDA.
- Used EDA and Advanced EDA (Pandas Profiling, Autoviz, Pandas Describe) to graphically represent the data and answer important questions which would help hotels customize their logistics to increase the bookings.
- Discovered important relation between Booking Cancellation rate and Advanced Booking Deposits, it was surprising that the cancellation rate in few segments was high despite the application of a deposit.
- Created Correlation matrix using Pearson and Spearman Method and also found highly correlated parameters which gave useful insights into the data
- Found the most important features which contributed to the decision making of the customer.
- *Feature Engineering*: Created Pipeline for full data preprocessing of continuous and categorical data and used OneHotEncoder to encode the data.
- Used 4 ML models for prediction - Linear Regression, Random Forest classifier, Logistic Regression and XGBoost, did Hyperparameter tuning of the most accurate model(Random Forest Classifier) to further increase accuracy.
- Got Feature importance of several parameters in the Data using eli5 library
