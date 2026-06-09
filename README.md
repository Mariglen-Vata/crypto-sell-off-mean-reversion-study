# Crypto Sell-Off Mean Reversion Study

This project investigates whether large daily crypto sell-offs are followed by short-term mean reversion across BTC, ETH and SOL.

The analysis focuses on daily sell-offs of 10% or more and examines forward returns over 1-day, 3-day, 7-day and 30-day horizons. It also tests whether results improve when the asset remains above its 50-day moving average, and whether deeper sell-off thresholds lead to stronger rebounds.

## Key Questions

- Do large daily crypto sell-offs lead to short-term rebounds?
- Are BTC, ETH and SOL affected differently?
- Does a 50-day moving average trend filter improve results?
- Do deeper sell-offs produce stronger mean-reversion returns?

## Main Findings

BTC showed the cleanest short-term mean-reversion profile, especially over the 1-day horizon.

SOL showed the strongest upside potential, particularly over longer forward-return horizons, but also carried much greater downside risk.

ETH appeared weaker under this framework, especially over the 7-day and 30-day horizons.

The 50-day moving average filter appeared useful for separating higher-quality sell-off events, especially for BTC and SOL, but stricter filters reduced the sample size.

## Tools Used

- Python
- pandas
- matplotlib
- yfinance
- Google Colab

## Important Limitations

This is a historical and educational research project, not financial advice. The analysis does not include transaction costs, slippage, funding costs, position sizing, stop losses or full portfolio-level backtesting.

Crypto trades 24/7, so daily closing prices depend on the data provider’s candle convention.
