#**Bike Sharing Demand Prediction Capstone Project**
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Project tile - Seoul Bike Sharing Demand Prediction
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Description:
This is a supervised ML (regression) capstone project on bike sharing demand prediction given by Alma Better.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Problem statement:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Dataset description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:

Date : year-month-day
Rented Bike count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity - %
Windspeed - m/s
Visibility - 10m
Dew point temperature - Celsius
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
rainbow
Conclusion:
EDA insights:

Most number of bikes are rented in the Summer season and the lowest in the winter season.
Over 96% of the bikes are rented on days that are considered as No Holiday.
Most number of bikes are rented in the temperature range of 15 degrees to 30 degrees.
Most number of bikes are rented when there is no snowfall or rainfall.
Majority of the bikes are rented for a humidity percentage range of 30 to 70.
The highest number of bike rentals have been done in the 18th hour, i.e 6pm, and lowest in the 4th hour, i.e 4am.
Most of the bike rentals have been made when there is high visibility.
Results from ML models:

Random Forest Regression is the best performing model with an r2 score of 0.6645.
Lasso Regression(L1 regularization) is the worst performing model with an r2 score of 0.4264.
Actual vs Prediction visualisation is done for all the 4 models.
All 4 models have been explained with the help of SHAP library.
Temperature and Hour are the two most important factors according to all the models.
Challenges faced:

Removing Outliers.
Encoding the categorical columns.
Removing Multicollinearity from the dataset.
Choosing Model explainability technique.
rainbow

For further information you can check the google colab file added in the repository.

If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.

You can also reach out to me for project collaborations.

My Email Id - syedshabbir107@gmail.com

My LinkedIn profile - Profile

Thankyou for tagging along to the end.
