# Autonomous Portfolio Rebalancing Agent

## Overview
This project demonstrates how financial modeling and artificial intelligence can work together to create an adaptive trading system. It focuses on building a data-driven portfolio optimization and rebalancing process based on Modern Portfolio Theory (MPT), and sets the foundation for future integration of autonomous reasoning agents.

The idea is to show how quantitative methods can evolve into intelligent systems capable of analyzing market data, optimizing portfolios, and adapting strategies as conditions change.

## Project Highlights

- Collects real financial data from Yahoo Finance.
- Uses statistical models to find the best portfolio mix for maximum risk-adjusted return.
- Simulates rebalancing of the portfolio over time.
- Visualizes performance using cumulative returns and volatility analysis.
- Designed to evolve into an AI-powered system that can make autonomous trading decisions.

---

## Concept
The system begins by analyzing historical stock prices to understand how each asset performs over time. It then applies portfolio optimization methods to balance risk and reward. The strategy is tested through simulated rebalancing, where portfolio weights are periodically updated to maintain optimal performance.

In future versions, this system will be expanded to include autonomous agents capable of gathering data, interpreting market trends, and making informed trading adjustments without manual input.

---

## Data and Methods

### Data Collection
- Source: Yahoo Finance API
- Example assets: RELIANCE.NS, INFY.NS, HDFCBANK.NS, ICICIBANK.NS

### Optimization
- Computes daily and annualized returns.
- Calculates volatility and correlations between assets.
- Finds the portfolio weights that maximize the Sharpe ratio while keeping total investment constant.

### Performance Evaluation
- Annualized Return
- Annualized Volatility
- Sharpe Ratio
- Cumulative Return

### Rebalancing
- Simulates portfolio updates at regular intervals.
- Visualizes how the portfolio value evolves through time.

---

## Future Direction
The next step is to integrate artificial intelligence for autonomous decision-making. Future components may include:

- Agents that collect and interpret financial and news data.
- Reinforcement learning for dynamic strategy optimization.
- A reasoning layer powered by large language models to adjust portfolio risk based on macroeconomic trends.
- A dashboard to visualize performance and decision processes in real time.

---

## Installation and Usage

### 1. Install Required Packages
```bash
pip install -r requirements.txt
```

### 2. Run the Project
Open the notebook `main_analysis.ipynb` in Jupyter or VS Code and run all cells.

### 3. Customize the Data
Modify the list of stock symbols to analyze different markets or assets.

### 4. View the Results
Graphs showing portfolio growth and rebalancing performance will be displayed after execution.

---

## Tools and Libraries
- Python 3.10+
- pandas, numpy, scipy, yfinance, matplotlib
- (Optional for AI integration): LangChain, AutoGen, OpenAI API

---

## Author
Developed to explore how financial modeling and artificial intelligence can combine to create autonomous systems for quantitative decision-making.
