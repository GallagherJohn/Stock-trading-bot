# Stock-trading-bot

This program makes use of the Alpha Vantage API to get the daily RSI of SPY and the latest price of SPY. You'll need to sign up for a free API key and replace "YOUR_API_KEY" with your own API key in the code. The program makes a request to the API every hour, checks the daily RSI of SPY, and places a buy order for 1 share of $SPY when price is oversold, and places a sell order for 1 shre of $SPY when price is overbought. 

The functions place_buy_order and place_sell_order must be modified by user to reflect their own personal account information. 
