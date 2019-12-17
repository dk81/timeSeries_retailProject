# Time Series Analysis Project For Retail Forecasting
---

These files was for a (first) school project. The three part notebook files does contain a lot of experimental items where I try out different forecasting models.


**Brief**

A retail store is requesting assistance in forecasting their third quarter (Q3) profits.

This retail store sells office supplies, technology products and furniture.


# Topics
---

* Notes About The Three Part Notebook Files
* Reworked Version Of Project

&nbsp;

# Notes About The Three Part Notebook Files
---

I have separated the project into three (Colab) notebooks. 

The first notebook consists of me obtaining number of orders for each product category, profits for each category, number of orders for each region and for each market. Essentially I was doing exploratory data analysis (EDA) trying to see what to further investigate.

In notebook two, I get involved with the forecasting models. The `auto_arima()` function from `pyramid.arima` is used to forecast Q3 (overall) monthly profits. I use Seasonal Autoregressive Moving Average (SARIMA) models for forecasting to account for seasonality within a calendar year and for accounting for general trends.

Notebook three goes a bit deeper and does forecasting Q3 profits for each product category. I use one SARIMA model for forecasting Q# profits on office supplies, a different SARIMA model for technology products and a different third model for furniture.



# Reworked Version Of Project
---

A reworked version of project with less clutter coming soon.
