# Trader Behavior vs Market Sentiment Analysis

## Overview

This project analyzes how trader performance and behavior change under different market sentiment conditions using a Fear & Greed Index dataset combined with trading activity data.

The analysis focuses on:

* Performance differences during Fear vs Greed periods
* Behavioral shifts in leverage, trading frequency, and position sizes
* Trader segmentation and strategy insights

---

## Dataset

1. **Fear & Greed Index**

   * Daily sentiment score (0–100)
   * Categorized into Fear, Neutral, Greed

2. **Trading Dataset**

   * Timestamp
   * Trader ID
   * PnL
   * Position size
   * Leverage
   * Trade side (Long/Short)

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/trader-sentiment-analysis.git
cd trader-sentiment-analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## How to Run

Place datasets in the project folder:

* fear_greed_index.csv
* trades.csv

Run the script:

```bash
python analysis.py
```

Charts will display automatically and metrics will print in the terminal.

---

## Project Structure

```
├── analysis.py
├── fear_greed_index.csv
├── trades.csv
├── README.md
```

---

## Key Outputs

* Performance comparison by sentiment
* Trader segmentation analysis
* Behavioral metrics
* Strategy recommendations
* Profitability prediction model (optional)

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
