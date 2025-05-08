# Elon Musk & Tesla Stock Analysis

This project investigates the impact of Elon Musk's follower trends and external events on Tesla (TSLA) stock performance. It includes data scraping, return calculations, and exploratory analysis across multiple Jupyter notebooks.

## Table of Contents

1. [Project Overview](#project-overview)
2. [File Descriptions](#file-descriptions)
3. [Data Sources](#data-sources)

## Project Overview

We explore how Elon Musk’s online influence—particularly Twitter follower growth—and external market events correlate with TSLA stock behavior. Our goal is to analyze volatility, return patterns, and potential investor sentiment shifts.

## File Descriptions

### Codes:

- `3250-project-data.ipynb`: Final compiled analysis across all research questions
- `3250-q1.ipynb`: Analysis Question 1 – Initial trends and correlations
- `3250-q2.ipynb`: Analysis Question 2 – Volatility during key periods
- `3250-q3.ipynb`: Analysis Question 3 – Predicting stock movement using features
- 'time-series-forecast.ipynb': Analysis of

### Data:

- `elon_followers.csv`: Twitter follower count of Elon Musk over time including his ~daily increase
- `project_checkin_data.csv`: Combined and cleaned dataset for modeling
- `tesla&market_returns.csv`: Daily returns for TSLA and the S&P 500
- `TSLA.csv`: Raw Tesla stock price data

- `README.md`: Documentation of project structure and purpose

## Data Sources

- **Elon Musk Twitter Follower Data:**  
  Scraped from: [https://www.statswithsasa.com/2024/09/18/elon-musk-definitely-tweets-too-much/#section1](https://www.statswithsasa.com/2024/09/18/elon-musk-definitely-tweets-too-much/#section1)

- **Tesla Stock Prices:**  
  Scrape Tesla stock prices using: [Yahoo Finance](https://finance.yahoo.com/quote/TSLA/history).

## Up to Date Data Dictionary

| Field                  | Type                 | Description                                                                  |
| ---------------------- | -------------------- | ---------------------------------------------------------------------------- |
| `Date`                 | Date                 | The day of the year                                                          |
| `TSLA_Open`            | Numeric              | Tesla opening stock price for the day                                        |
| `TSLA_High`            | Numeric              | Tesla highest stock price for the day                                        |
| `TSLA_Low`             | Numeric              | Tesla lowest stock price for the day                                         |
| `TSLA_Close`           | Numeric              | Tesla closing stock price for the day                                        |
| `TSLA_Adj Close`       | Numeric              | Tesla closing price after adjustment for all applicable splits and dividends |
| `TSLA_Volume`          | Numeric              | Number of Tesla shares traded for the day                                    |
| `TSLA_Return`          | Numeric (Calculated) | (Adj Close – Open) / Open — Tesla daily return                               |
| `GSPC_Open`            | Numeric              | S&P 500 opening stock price for the day                                      |
| `GSPC_High`            | Numeric              | S&P 500 highest stock price for the day                                      |
| `GSPC_Low`             | Numeric              | S&P 500 lowest stock price for the day                                       |
| `GSPC_Close`           | Numeric              | S&P 500 closing stock price for the day                                      |
| `GSPC_Adj Close`       | Numeric              | S&P 500 closing price after adjustment for splits and dividends              |
| `GSPC_Volume`          | Numeric              | Number of S&P 500 shares traded for the day                                  |
| `GSPC_Return`          | Numeric (Calculated) | (Adj Close – Open) / Open — S&P 500 daily return                             |
| `Change_in_Followers`  | Numeric              | Number of Elon Musk followers gained or lost on a given day                  |
| `TSLA_positive_return` | Numeric              | 1 if return was positive, 0 if it was negative                               |
