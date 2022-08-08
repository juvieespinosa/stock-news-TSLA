STOCK ALERT - TESLA

A stock alert trading news program, written in Python, that notifies by SMS if a specific stock is either 5% up or down between the stock's yesterday's closing price and the day before closing price. 


import requests
from twilio.rest import Client


STOCK_NAME = "TSLA"
COMPANY_NAME = "Tesla Inc"

STOCK_ENDPOINT = "https://www.alphavantage.co/query"
NEWS_ENDPOINT = "https://newsapi.org/v2/everything"
