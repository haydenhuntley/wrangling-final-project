# Elon Musk & Tesla Stock Analysis

This project investigates the impact of Elon Musk's follower trends and external events on Tesla (TSLA) stock performance. It includes data scraping, return calculations, and exploratory analysis across multiple Jupyter notebooks.

## Table of Contents

1. [Project Overview](#project-overview)
2. [File Descriptions](#file-descriptions)
3. [Data Sources](#data-sources)
4. [Setup Instructions](#setup-instructions)

## Project Overview

We explore how Elon Musk’s online influence—particularly Twitter follower growth—and external market events correlate with TSLA stock behavior. Our goal is to analyze volatility, return patterns, and potential investor sentiment shifts.

## File Descriptions

### Codes:

- `3250-project-data.ipynb`: Final compiled analysis across all research questions
- `3250-q1.ipynb`: Analysis Question 1 – Initial trends and correlations
- `3250-q2.ipynb`: Analysis Question 2 – Volatility during key periods
- `3250-q3.ipynb`: Analysis Question 3 – Predicting stock movement using features

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

## Setup Instructions

1. Clone the repository or download the files.
2. Create and activate a virtual environment (optional but recommended).
3. Install dependencies:
