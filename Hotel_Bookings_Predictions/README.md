# Hotel_Bookings_Predictions

### Project: 
Forecast the ratio between the number of bookings and number of clickouts.

### Description: 
In this notebook I showcase my skills in tackling a data science project which focuses on the explorative data analysis and modeling of a sparse dataset.
The dataset spans 10 days between 2023.08.01 to 2023.08.10 and contains information on different hotels and the daily number of clicks and bookings made by customers.
The goal of the case study is to forecast the conversion rate, i.e. the ratio between the number of bookings and the number of clickouts, in 2023.08.11 for each hotel-advertiser couple present in the dataset. 
After the phases of data cleaning, EDA, and feature engineering, the best strategy presented in this notebook to predict the target variable, consists of a first classification model and a subsequent regression model, mimicking the concept of a Hurdle modle. 
The classification model predicts if the conversion rate is going to be zero or higher than zero. The regression model improves the conversion rate predictions for the hotel-advertiser couples that were predicted to have a conversion rate higher than zero.
I conclude the notebook with a summary of the results and the possible next steps.

