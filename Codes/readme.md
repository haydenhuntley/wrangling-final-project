## Elon Musk, TSLA & Market Reactions – Analysis Walkthrough

### 3250-q1: Has Elon Musk’s increased media presence significantly impacted Tesla’s stock returns or volatility?​?

**Notebook:** `3250-q1.ipynb`
**Code Summary:**

- Imports required libraries
- Loads a dataset
- Calculate descriptive statistics
- Create line chart of Tesla's daily returns
- Do a Chi-Squared test to see if there is a relationship between change in Musk followers and TSLA stock returns
- Create a box plot with separate bins for followers gain and amount of change in TSLA stock

**Purpose:** Determine if there is a statistical relationship between social media influence and stock performance.

### 3250-q2: How does Tesla’s daily return volatility compare to that of the S&P 500 during key market events?

**Notebook:** `3250-q2.ipynb`
**Code Summary:**

- Create conditions for large market events
- Calculate standard devation for the TSLA stock during these large market events
- Create boxplots to show the deviation between the market and TSLA stock during market events

**Purpose:** Examine what impact large market events have on TSLA compared to the market.

### 3250-q3: Can we predict whether Tesla’s stock return will be positive or negative based on S&P returns and Elon’s twitter following?

**Notebook:** `3250-q3.ipynb`
**Code Summary:**

- Created a confusion matrix
- Created a ROC curve using logistic regression to deterumin AUC

**Purpose:** Determine whether we can predict if the TLSA stock will be positive or negative using Elon's follower count and the market price.

### time-series-forecast: Continuation of Q3. Can we predict the price of TSLA stock over time?

**Notebook:** `time-series-forecast.ipynb`
**Code Summary:**

- Calculated the MAE for moving average, simple exponential smoothing with alpha of 0.5, additive exponential smoothing and TBATS
- Moving average was the best so created a forecast based of MAE
- Made a line chart with the forecast

**Purpose:** Predict the TSLA stock return based on the market and Elon's followers.
