# Hyperliquid Trader Behavior vs Market Sentiment Analysis

## Objective

The goal of this project is to analyze how **market sentiment (Fear vs Greed)** relates to **trader behavior and performance** on the Hyperliquid platform.
By combining sentiment data with trading activity, the analysis aims to uncover patterns that can inform smarter trading decisions and risk management strategies.

---

## Datasets

### 1. Fear & Greed Index

Provides a daily sentiment score (0–100) representing overall market psychology.
The score is categorized into:

* Fear (0–40)
* Neutral (40–60)
* Greed (60–100)

### 2. Historical Trading Data

Contains trading activity at the daily level, including metrics such as:

* Date
* Trading activity indicators
* Performance-related fields (e.g., PnL if available)
* Risk metrics (e.g., leverage or position size if present)

---

## Methodology

### Data Preparation

* Loaded both datasets and inspected structure, missing values, and duplicates.
* Converted timestamps to a daily format.
* Merged datasets using the date column.
* Created key metrics such as:

  * Daily trading activity
  * Performance metrics (PnL / win rate where available)
  * Risk indicators (leverage / position size)
  * Sentiment buckets

### Analysis

The analysis focuses on:

1. Performance differences across sentiment regimes
2. Behavioral changes in trading activity and risk-taking
3. Segmenting traders based on behavior and consistency

Charts and tables are used to support each finding.

---

## Key Questions Answered

* Does profitability differ during Fear vs Greed markets?
* Do traders increase risk or activity when sentiment shifts?
* Which trader segments behave differently across regimes?

---

## Results

The analysis highlights clear relationships between sentiment and trader behavior, including shifts in activity levels and risk exposure across different market conditions.

---

## Strategy Implications

Findings are translated into actionable rules such as sentiment-aware risk adjustments and segment-based trading strategies.

---

## How to Run

1. Place datasets in the project folder:

   * `fear_greed_index.csv`
   * `historical_data.csv`

2. Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Run the analysis script:

```bash
python analysis.py
```


pip install streamlit pandas numpy matplotlib scikit-learn
streamlit run app.py
---

## Tools Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## Outcome

This project demonstrates how sentiment-driven insights can improve trading strategy design by linking market psychology to measurable behavior and performance metrics.
