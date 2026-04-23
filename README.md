# Toy-trading-agent
## Overview
Develop an intelligent trading assistant that leverages financial data analysis and news sentiment to make strategic investment decisions across multiple companies.

### Core Functionality

- **Financial Strategy**
  - Analyze company financial reports
  - Develop a trading strategy based on report metrics
  - Identify a long-term pattern for inclrease/decrease of stock price

- **News Processing Engine**
  - Process daily news related to target companies
  - Filter relevant news from noise
  - Extract actionable buy/sell signals from news sentiment

- **Decision Making System**
  - Implement logic combining financial analysis and news signals
  - Generate daily buy/hold/sell recommendations

- **Position Management**
  - Maintain maximum position of maximum of 1 share at a time (easier to calculate profit/loss)
  - The agent should only know the stock prices prior to the current trading day
  - Record entry and exit points

- **Multi-Asset Management** 
  - Monitor all 5 companies simultaneously
  - Implement logic to sell one position to buy another (assume any stock can be exchanged for another company's stock)
  - Optimize portfolio allocation across available assets
