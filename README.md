# AirportTaxiDemandPrediction

Airport Taxi Demand Forecast ML problem 

I just wanted to demonstrate how typical Time-series techniques and algorithms won't fair well on all seemingly time-series forecasting problems. Time Series Extrpolation Techniques like Auto-Regression (ARIMA and cousins) works <b> ONLY </b>

<ul>
<li> if the domain knowledge is not influencing the traits of the series for instance the trend </li>
<li> if all time steps/lags can be framed as equally time-spaced data points without lot of gaps </li>
</ul>
  
For instance consider this use case, we wanted to forecast the non-transit passengers who will use taxi as their mode of transport for the coming xmas eve and the xmas day.
How would you frame this as a simple time-series , even if you did will it work ? If we took all the previous xmas days and frame it as a time step, it will be too less training data to do anything meaningful.

I worked with a large south east asian country's airport group, unfortunately I can share only certain information but I will drive my point with same synthentic data.
