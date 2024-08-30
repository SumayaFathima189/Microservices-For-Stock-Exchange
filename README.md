# Application For Stock Trading with Alpaca API Using Python
## Introduction
This repository contains a set of Python scripts that utilize the Alpaca API to perform various tasks related to stock trading. These scripts are designed to be modular and can be used together to build a comprehensive stock trading application.
### 1. Install Dependencies:
pip install alpaca-trade-api
### 2. Set Alpaca API Credentials:
Replace the ALPACA_API_KEY and ALPACA_SECRET_KEY variables in the scripts with your own API credentials.
### 3. Run the Scripts:
You can now run the individual scripts based on your requirements.

## Microservices Overview and Function Signature:
## *1. Retrieve Stock Information*
Description: This microservice allows you to retrieve detailed information about a specific stock.

def retrieve_stock_info(symbol: str) -> dict: """ Retrieves detailed information about a stock.
```Args:
    symbol (str): The stock symbol (e.g., AAPL).

Returns:
    dict: A dictionary containing stock information.
"""
...```
