# Time_Series Guide

Instructions: Include a Markdown that summarizes your models and findings and include this report in your GitHub repo.

Trend of 2015 to the present of the settle_df dataframe is volatile, which also has two major market bubbles. The plot created
from the ARMA model had a 5 day returns forecast that had dropped the lowest towards the beginning of the chart. This beginning part of the 5 day returns forecast was also the most volatile. In opposite fashion, the ARIMA and GARCH model(s) had a plot with consistent volatility and price action across the time displayed, 5 days. Based on the time series analysis, I would purchase the yen now since the value is expected to rise through the next 5 days. 
The risk of the yen would be expected to increase since the price action is headed towards a less potentially profitable purchase afterthe price increases.
I wouldn't use these models for trading. The Out-of-Sample performance has a higher mse than the In-Sample performance so the model performs worse compared to the In-Sample.
