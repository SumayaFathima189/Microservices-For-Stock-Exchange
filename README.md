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
### *Retrieve Stock Information*
Description: This microservice allows you to retrieve detailed information about a specific stock.

def retrieve_stock_info(symbol: str) -> dict: """ Retrieves detailed information about a stock.
```
Args:
    symbol (str): The stock symbol (e.g., AAPL).

Returns:
    dict: A dictionary containing stock information.
"""
...
```

### *Place Buy Order*
Description: This microservice enables you to place a buy order for a specific stock.

def place_buy_order(symbol: str, qty: int) -> None: """ Places a buy order for a specific stock.
```
Args:
    symbol (str): The stock symbol (e.g., AAPL).
    qty (int): The quantity of shares to buy.

Returns:
    None
"""
...
```

### *Place Sell Order*
Description: This microservice allows you to place a sell order for a specific stock.

def place_sell_order(symbol: str, qty: int) -> None: """ Places a sell order for a specific stock.
```
Args:
    symbol (str): The stock symbol (e.g., AAPL).
    qty (int): The quantity of shares to sell.

Returns:
    None
"""
...
```

### *Retrieve Order History*
Description: This microservice retrieves the order history for your account.

def retrieve_and_display_orders() -> None: """ Retrieves and displays the order history for your account.
```
Returns:
    None
"""
...
```

### *Add to Cart*
Description: This microservice allows you to add stocks to a cart for later processing.

def add_to_cart(stock_symbol: str) -> None: """ Adds a stock to the cart.
```
Args:
    stock_symbol (str): The stock symbol (e.g., AAPL).

Returns:
    None
"""
...
```

### *View Cart*
Description: This microservice displays the contents of the cart.

def view_cart() -> None: """ Displays the contents of the cart.
```
Returns:
    None
"""
...
```

### *Buy Stocks*
Description: This microservice allows you to buy the stocks in your cart.

def buy_stocks() -> None: """ Places buy orders for the stocks in the cart.
```
Returns:
    None
"""
...
```

### Note
Ensure you have valid Alpaca API credentials to use these services. Use the Paper Trading API for testing.

