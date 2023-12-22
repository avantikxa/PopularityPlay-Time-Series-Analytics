# Sports Popularity Forecasting using Time Series Analysis

## Overview

The project focuses on predicting the popularity trends of major sports leagues, specifically the Indian Premier League (IPL) in India and the National Football League (NFL) in the United States, using univariate time series forecasting models.

## Problem Statement

The objective of the project is to compare and contrast the popularity of major sports leagues in the United States and India, providing valuable insights for businesses involved in advertising, marketing, or investing in these leagues. The analysis aims to make confident predictions about which league is growing faster, helping stakeholders make informed decisions.

## Data

The dataset was sourced from Google Trends, providing monthly popularity scores for search terms related to IPL and NFL from November 2007 to October 2022. The scores are presented on a relative index of 0-100, with 100 representing the peak popularity of the search term. The data was filtered for searches in the United States and India.

## Methodology

1. **Data Sourcing and Cleaning:**
   - Dataset obtained from Google Trends and Yahoo Finance.
   - Cleaning involved handling missing values and ensuring data consistency.

2. **Exploratory Data Analysis (EDA):**
   - Visualized time series data to observe trends and patterns.
   - Tested for stationarity using the Augmented Dickey-Fuller Test.
   - Applied differencing to transform non-stationary data into stationary.

3. **Model Building:**
   - Utilized Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots to determine model orders.
   - Developed ARIMA and SARIMA models for IPL and NFL datasets, considering seasonality and differencing.

4. **Model Validation and Forecasting:**
   - Evaluated model performance using Akaike's Information Criteria (AIC).
   - Forecasted future popularity trends and compared them with the original data.

5. **Time Series Analysis on Stock Returns:**
   - Conducted analysis on PepsiCo stock returns, a long-standing sponsor of the leagues.
   - Explored fluctuations dependent on the seasonality of sports leagues' playing seasons.


## References

- [Research Paper: Forecasting Sports Popularity - Application of Time Series Analysis](https://www.researchgate.net/publication/319384255_Forecasting_Sports_Popularity_Application_of_Time_Series_Analysis)
- Google Trends: [IPL](https://trends.google.com/trends/explore?date=2007-09-24%202022-09-24&geo=IN&q=ipl) and [NFL](https://trends.google.com/trends/explore?date=2007-09-24%202022-09-24&geo=US&q=nfl)

