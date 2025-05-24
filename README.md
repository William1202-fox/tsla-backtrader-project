# TSLA 20-Day Bollinger Band Mean-Reversion

| Metric             | Value       |
|--------------------|------------|
| Annualized return  | **44.94 %** |
| Sharpe ratio       | **0.06**   |
| Max drawdown       | **-73.6 %**  |
| Period             | 2010-01-01 ~ 2025-05-21 |

**Strategy Logic**

1. 使用 20 日布林通道（±2 標準差）
2. 收盤價跌到下通道時，用可用現金 30% 買進 TSLA
3. 不設賣出條件，全部持有到 2025/5/21 強制平倉
4. 每筆交易收取 0.1% 手續費

**Equity Curve and Drawdown**

![TSLA equity](images/tsla_equity_dd.png)
