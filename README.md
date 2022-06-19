# Time Series Analysis & Forecasting on Metro Traffic Volume in Minneapolis
***

## Dataset Information

Data taken from the UCI Machine Learning Repository

Hourly Interstate 94 Westbound traffic volume for MN DoT ATR station 301, roughly midway between Minneapolis and St Paul, MN. Hourly weather features and holidays included for impacts on traffic volume.

## Project Overview

This project is for the completion of the Time Series Analysis course at the University of Barcelona for the partial fulfillment of Master of Science in Fundamentals of Data Science.

The focus of this project is the application of the core competencies and concepts of the course, including:

<ol>
    <li> Descriptive analysis of time series. trends and cycles</li>
    <li> Modeling time series. Stationarity. Auto-correlation. </li>
    <li> Prediction. Partial autocorrelation </li>
    <li> Statistics of stationary time series </li>
    <li> ARMA Models </li>
    <li> Calibration of ARMA Models </li>
    <li> Non-Stationarity. ARIMA Models </li>
    <li> Seasonality. SARIMA Models </li>
    <li> Long Memory. ARFIME Models </li>
    <li> Heterocedasticity. GARCH Models</li>
    <li> Intervention Analysis</li>
    <li> State-Space Models. Kalman recursions</li>
</ol>

## Attribute Information

feature | data type | description
---|---|---
holiday | Categorical | US National holidays plus regional holiday, Minnesota State Fair
temp | Numeric | Average temp in kelvin
rain_1h | Numeric | Amount in mm of rain that occurred in the hour
snow_1h | Numeric | Amount in mm of snow that occurred in the hour
clouds_all | Numeric | Percentage of cloud cover
weather_main | Categorical | Short textual description of the current weather
weather_description | Categorical | Longer textual description of the current weather
date_time | DateTime | Hour of the data collected in local CST time
traffic_volume | Numeric | Hourly I-94 ATR 301 reported westbound traffic volume
