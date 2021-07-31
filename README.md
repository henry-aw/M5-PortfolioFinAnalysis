# *Module 5 Challenge*
## Financial Planners for Emergencies and Retirement
**Welcome to my Module 5 Challenge repository. Check out the financial analysis tools I created to plan for emergencies and retirement.**

---

This is a jupyter lab application that performs calculations and creates visualizations for financial analysis of potential portfolios to plan for emergencies and retirement.
1. A financial planner for emergencies. Use this tool to visual current savings, then determine if there is enough held in reserves for an emergency fund.
2. A financial planner for retirement. This tool will forecast the performance of retirement portfolios over 30 years and 10 years, with different weights tested. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.


---

## Technologies & Usage
This project leverage Python 3.7, Jupyter Lab and Alpaca API with the following libraries and dependencies:
- import os
- import requests
- import json
- import pandas as pd
- drom dotenv import load_dotenv
- import alpaca_trade_api as tradeapi
- from MCForecastTools import MCSimulation
- %matplotlib inline

