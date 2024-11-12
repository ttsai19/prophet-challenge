# Prophet Challenge: MercadoLibre Search Traffic & Stock Analysis

## Overview

This project aims to analyze search traffic and stock data for **MercadoLibre**, the most popular e-commerce platform in Latin America, using time series analysis with **Prophet**. By identifying seasonal trends, unusual patterns, and correlations with stock prices, the analysis seeks to help MercadoLibre better understand user interest patterns and their potential link to stock performance.

## Data

The data sources used in this project are:
1. **Google Search Trends** - Hourly search data for "MercadoLibre" between 2015 and 2020.
2. **MercadoLibre Stock Prices** - Daily closing stock price data from 2015 to 2020.

## Project Structure

The analysis is divided into the following sections:

1. **Step 1: Identify Unusual Patterns in Google Search Traffic**
   - Analyzed if search traffic increased during May 2020 when quarterly financial results were announced.
   - Compared the search traffic of May 2020 to the monthly median across all months.

2. **Step 2: Mine Search Traffic for Seasonality**
   - Examined trends in search traffic by:
     - Hour of the day
     - Day of the week
     - Week of the year
   - Identified patterns in user interest based on time, aiding in potential marketing strategies.

3. **Step 3: Analyze Relationship with Stock Price**
   - Investigated if there was a relationship between search traffic and stock price.
   - Sliced the data to the first half of 2020 and compared trends in search traffic and stock closing prices.

4. **Step 4: Forecast with Prophet Model**
   - Built a forecasting model using Prophet to predict future search traffic.
   - Analyzed seasonal components to determine:
     - The time of day with the highest user interest
     - The day of the week with the most traffic
     - The time of year with the lowest search traffic

## Results

1. **Patterns in Search Traffic:**
   - Higher search traffic was observed during May 2020, likely linked to the release of financial results.
   - Search traffic follows distinct seasonal trends by time of day, day of the week, and week of the year, peaking around midnight on Tuesdays.

2. **Relationship with Stock Price:**
   - No strong correlation was found between lagged search traffic and stock volatility or returns.

3. **Forecast for Search Traffic:**
   - The near-term forecast for search interest in MercadoLibre predicts a slight decrease.

## Questions & Answers

### Step 1
- **Did the Google search traffic increase during the month that MercadoLibre released its financial results?**
  - Yes, May 2020 showed a noticeable increase in search traffic, around 8.5% higher than the monthly median.

### Step 2
- **Are there any time-based trends in the data?**
  - Yes, traffic peaks at midnight, is highest on Tuesdays, and increases during the holiday season.

### Step 3
- **Do both time series indicate a common trend that’s consistent with this narrative?**
  - Yes, both search traffic and stock prices trended upwards in early 2020.

- **Is there a predictable relationship between lagged search traffic and stock volatility or returns?**
  - No significant relationship was observed.

### Step 4
- **How's the near-term forecast for MercadoLibre’s popularity?**
  - The model predicts a slight decrease in search traffic in the coming months.

