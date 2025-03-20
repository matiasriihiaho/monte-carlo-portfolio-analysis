# monte-carlo-portfolio-analysis
A comprehensive analysis of portfolio performance and survival based on different asset allocations, using historical data and Monte Carlo simulations. This project explores the relationship between fixed income, equity, inflation, and interest rates, evaluating various financial metrics to compare investment strategies.

| Strategy                  | Nominal End Balance   | Real End Balance   | Nominal Annual Return   | Real Annual Return   | Volatility    | Sharpe Ratio              |   Sortino Ratio | Max Drawdown   | Perpetual SWR   |
|:--------------------------|:----------------------|:-------------------|:------------------------|:---------------------|:--------------|:--------------------------|----------------:|:---------------|:----------------|
| Aggressive Growth (20/80) | €509.29               | €475.22            | 6.19%                   | 5.96%                | 12.33%        | **0.4851228914721134** ⬆️ |        0.441193 | -42.78%        | 4.96%           |
| Balanced (50/50)          | €333.58               | €311.31            | 4.42%                   | 4.19%                | **9.03%** ⬆️  | 0.4653176089631662        |        0.443823 | -30.76%        | 3.19%           |
| Conservative (60/40)      | €280.92               | €262.19            | 3.78%                   | 3.55%                | 8.22%         | 0.4319451614148406        |        0.418081 | -27.64%        | 2.55%           |
| Equity (0/100)            | €630.36               | €588.22            | **7.27%** ⬆️            | 7.04%                | 14.94%        | 0.4730196325364436        |        0.421841 | -51.09%        | 6.04%           |
| Growth (40/60)            | €389.40               | €363.55            | 5.04%                   | 4.81%                | **10.01%** ⬇️ | 0.4813270851830343        |        0.444398 | -34.40%        | 3.81%           |
| Safe (80/20)              | €187.72               | €175.19            | **2.37%** ⬇️            | 2.14%                | 7.42%         | **0.2869342956761807** ⬇️ |        0.290792 | -25.81%        | 1.14%           |
