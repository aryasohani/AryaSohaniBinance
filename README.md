# AryaSohaniBinance
# Binance Futures Order Bot

## Overview
This is a **CLI-based Binance USDT-M Futures Trading Bot** developed using Python.  
The bot supports **multiple order types** (Market, Limit, Stop-Limit, OCO, TWAP, and Grid orders) and includes **robust input validation**, **structured logging**, and **clear documentation**.

It is designed to automate order execution strategies on Binance Futures using the official Binance API.

## Features

### Core Orders (Mandatory)
- **Market Orders:** Instantly executes at the current market price.  
- **Limit Orders:** Executes when the market reaches a specified price.

### Advanced Orders (Bonus)
- **Stop-Limit Orders:** Places a limit order once the stop price is reached.  
- **OCO Orders (One Cancels the Other):** Combines a stop-loss and take-profit order.  
- **TWAP (Time-Weighted Average Price):** Splits large orders into smaller timed chunks.  
- **Grid Strategy:** Automated buy-low/sell-high within a price range.


