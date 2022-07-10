# Lesson_12
# Primary application file

Produce a Google colab file analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.


---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Jupyter Lab 
    Version 3.2.9
    
Google.colab

---

## General information about analysis.

First you need to configure Google Colab workspace.  After configuring Google Colab try to find unusual patterns in hourly google search traffic.

After that you mine the search traffic data for seasonality and try to find search traffic to stock price patterns.

Then you creat a time series model with Prophet and forecast revenue by using time series models.






---

## Information about datasets

Data frame for trends in search history:

df_mercado_trends

Data frame for May 2020 search history:

df_may_2020

Create hvplot for day of week search trends:

mean_daily_traffic

Create a data frame stock price:

df_mercado_stock

Concatenate the stock price and search trend data frames:

mercado_stock_trends_df

Adjust concatenated data frame to first half of 2020:

first_half_2020 

Create a prophet data frame for search trends:

mercado_prophet_df

Plot data for components in search trend data frame:

forecast_mercado_trends, figures_mercado_trends

Data frame for daily revenue:

df_mercado_sales

Create a Prophet data frame for revenue:

mercado_sales_prophet_df




---

## Libraries used in analysis

pandas

numpy

holoviews

Prophet

hvplot

datetime

metaplotlib

panel

---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/license.txt)
