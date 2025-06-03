# Stock News Sentiment and Price Movement Correlation Analysis

## Project Overview

This project analyzes the correlation between news sentiment and stock price movements. It aligns news headlines with stock price data by date, performs sentiment analysis on the news headlines, calculates daily stock returns, and investigates how sentiment scores correlate with stock returns.

---

## Features

- **Date Alignment:** Synchronizes news and stock price data by dates to enable meaningful comparison.
- **Sentiment Analysis:** Uses TextBlob to quantify the tone of news headlines into positive, negative, or neutral categories.
- **Stock Returns Calculation:** Computes daily percentage changes in closing stock prices to represent stock movement.
- **Correlation Analysis:** Examines statistical correlations between average daily news sentiment and daily stock returns.
- **Visualization:** Provides scatter plots to visualize the relationship between news sentiment and stock price changes.

---

## Installation

1. Clone the repository:

```bash
git clone <https://github.com/Liya-F/financial-news-data-discovery-w1.git>
cd <financial-news-data-discovery-w1>
```

2. Create and activate a Python virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

2. Install required packages from requirements.txt:

```bash
pip install -r requirements.txt
```

## Usage

- Place your datasets in the data/ directory:

raw_analyst_ratings.csv (news data)

TSLA_historical_data.csv (stock price data)

- Run the notebook files.