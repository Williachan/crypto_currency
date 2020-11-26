# Crypto currency

Everything related to crypto currency.

### cmc.ipynb

https://coinmarketcap.com/  
The API (basic plan) from this website does not allow to retrieve historical data.  
Small notebook (python) script for web-scraping Bitcoin (USD) historical daily data to participate to the challenge "Bitcoin $20K":  
Predict (three time slots of one hour) when the Bitcoin will hit $20,000 ($10,000 in BTC to Be Won).  

https://coinmarketcap.com/robots.txt  
User-agent: *  
Allow: /  

The data can be retrieved between 29/04/2013 (oldest date available) and now for the daily value of BTC (USD, but this is highly tunable).
The resulting dataframe consists of the timestamp, open, close, low and high values.
