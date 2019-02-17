# Jetrail-Time-Series-Project
Time Series Model to Forecast number of passengers, using ARIMA

## Problem Statement
Unicorn Investors wants to make an investment in a new form of transportation - JetRail. JetRail uses Jet propulsion technology to run rails and move people at a high speed! The investment would only make sense, if they can get more than 1 Million monthly users with in next 18 months. In order to help Unicorn Ventures in their decision, we need to forecast the traffic on JetRail for the next 7 months. we are provided with traffic data of JetRail since inception in the test file.

## Hypothesis Generation
Hypothesis generation helps us to point out the factors which might affect our dependent variable. Below are some of the hypotheses which I think can affect the passenger count(dependent variable for this time series problem) on the JetRail:

a.	There will be an increase in the traffic as the years pass by.
•	Explanation - Population has a general upward trend with time, so I can expect more people to travel by JetRail. Also, generally companies expand their businesses over time leading to more customers travelling through JetRail.

b.	The traffic will be high from May to October.
•	Explanation - Tourist visits generally increases during this time perion.

c.	Traffic on weekdays will be more as compared to weekends/holidays.
•	Explanation - People will go to office on weekdays and hence the traffic will be more

d.	Traffic during the peak hours will be high.
•	Explanation - People will travel to work, college.

We will try to validate each of these hypothesis based on the datasets

The ARIMA forecasting for a stationary time series is nothing but a linear (like a linear regression) equation.
## What is a stationary time series?
There are three basic criterion for a series to be classified as stationary series :
•	The mean of the time series should not be a function of time. It should be constant.
•	The variance of the time series should not be a function of time.
•	The covariance of the ith term and the (i+m)th term should not be a function of time.

