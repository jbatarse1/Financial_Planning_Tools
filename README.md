# Financial_Planning_Tools

Application developed to analyze stocks, bonds, cryptocurrency retirement planning and forecasting. 
This program runs a **Python** application within Jupyter Lab to perform 
financial planning analysis for the evaluation of a retirement portfolio. 

Monte Carlo Simulations are performed to evaluate return in a 30 year timeframe and a 10 year timeframe. 
Also, portfolio diversification is changed to determine possible outcomes.

Line and Bar Plots are created to visualize the information for better understanding and decision making.
When working in jupyter lab, ensure you activate hidden files by allowing notebook to access them via ```dotenv```.

Must have keys in a hidden file .env with keys listed

---

## Technologies

This application is developed on the **Python** *3.7.11 version*. It incorportates the following required 8 dependancies to run:

1. **import os**
2. **import requests**
3. **import json**
4. **import pandas as pd**
5. **from dotenv import load_dotenv**
6. **import alpaca_trade_api as tradeapi**
7. **from MCForecastTools import MCSimulation**
8. **%matplotlib inline**

---

## Installation Guide

The following installation must be performed before running the program. It include:


**Conda Installations:**

```conda install -c anaconda requests```

```conda install -c jmcmurry json```


**PIP Installations:**

```pip install python-dotenv```

```pip install alpaca-trade-api```


**Set Up Tool for Accessing APIs:**

```alternative.me.crypto/api/```

```data.nasdaq.com```

```alpaca.markets```


---

## Usage

To run this application, create a clone on the local desktop. Then, initiate your conda environment and 
open ```jupyter lab --ContentsManager.allow=hidden=True```. Now, you can run the notebook in jupyter lab and 
read hidden file with alpaca keys.

Steps for running application:

1st. Create a Financial Planner for Emergencies

    * Evaluate Crypto assets via Requests
    * Evaluate Stocks/Bonds portfolio using Alpaca SDK
    * Evaluate Emergency Fund


2nd. Create a Financial Planner for Retirement

    * Create Monte Carlo Simulation
    * Analyze Retirement Portfolio Forecasts

3rd. Review 30 year and 10 year Monte Carlo Simulations for stock and bonds porfolio: 
    
    * evaluate how the stocks/bonds porfolio values react relative to time and diversification.
    

The images below illustrates the results of the 30 year Monte Carlo simulations results:

<img width="467" alt="Screen Shot 2022-02-06 at 10 00 17 AM" src="https://user-images.githubusercontent.com/93550651/152694609-3ca905d7-e52b-4215-835d-b6f89bd38ba3.png">

<img width="515" alt="Screen Shot 2022-02-06 at 10 00 40 AM" src="https://user-images.githubusercontent.com/93550651/152694621-6b343815-9cc7-45bb-8ae2-7012080c1a3c.png">

## Contributors

Contributor: John Batarse  

Email: jbatarse@hotmail.com

LinkedIn: [Find me on LinkedIn](<https://www.linkedin.com/in/john-a-batarse-760a26116/>)


## License

Trilogy Education, LLC / UC Berkeley
