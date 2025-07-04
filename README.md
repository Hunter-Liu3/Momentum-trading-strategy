# Momentum Trading Strategy

A quantitative trading strategy that uses 20-day momentum to buy high-performing stocks and sell underperforming ones.

## Results
- **Strategy Return**: 1.66% over 2 years
- **S&P 500 Return**: 2.65% over 2 years  
- **Sharpe Ratio**: 0.13

## Files
- `momentum_strategy.ipynb` - Main analysis notebook
- `requirements.txt` - Required Python packages

## How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Run the Jupyter notebook: `jupyter notebook momentum_strategy.ipynb`

## Strategy Overview
This strategy:
1. Calculates 20-day momentum for a portfolio of stocks
2. Ranks stocks by momentum
3. Buys top 40% performers, sells bottom 40%
4. Rebalances monthly

## Key Learnings
- Momentum strategies can be challenging to implement profitably
- Transaction costs and market timing are crucial factors
- Risk-adjusted returns (Sharpe ratio) are as important as total returns