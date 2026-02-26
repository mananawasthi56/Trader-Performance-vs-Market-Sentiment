## Methodology

The analysis integrates daily market sentiment data with individual trade records.
First, timestamps were converted to a daily level to align both datasets.
Key metrics such as daily PnL, win rate, trade frequency, leverage usage, and position size were computed.

Sentiment scores were bucketed into:

* Fear (0–40)
* Neutral (40–60)
* Greed (60–100)

Trader behavior and performance were then compared across these sentiment regimes.
Additionally, traders were segmented by leverage usage, trading frequency, and performance consistency to identify behavioral patterns.

---

## Key Insights

1. **Performance varies with sentiment**
   Average PnL and win rate show noticeable differences across Fear and Greed periods, indicating that market psychology influences profitability.

2. **Behavior shifts in Greed periods**
   Trading frequency and leverage usage tend to increase during higher sentiment periods, suggesting more risk-taking behavior.

3. **High-leverage traders show higher variability**
   While they may achieve higher returns, their PnL dispersion is larger, indicating higher risk exposure.

---

## Strategy Recommendations

1. **Risk control during Fear markets**
   Reducing leverage during Fear periods can help manage drawdowns as volatility and uncertainty increase.

2. **Selective aggression during Greed markets**
   Higher trade frequency should be limited to traders with historically high win rates, as overtrading can reduce returns for inconsistent performers.

3. **Segment-based risk limits**
   Applying different leverage caps based on trader consistency can improve overall risk-adjusted performance.

---

## Conclusion

The study demonstrates that trader behavior is strongly linked to market sentiment.
Incorporating sentiment-aware risk management and segment-based strategies can improve both stability and profitability.
