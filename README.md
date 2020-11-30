# Crypto currency

Everything related to crypto currency.

### cmc.ipynb

source: https://coinmarketcap.com/  
The API (basic plan) from this website does not allow to retrieve historical data.  
Small notebook (python) script for web-scraping Bitcoin (USD) historical daily data to participate to the challenge "Bitcoin $20K":  
Predict (three time slots of one hour) when the Bitcoin will hit $20,000 ($10,000 in BTC to Be Won).  

https://coinmarketcap.com/robots.txt  
User-agent: *  
Allow: /  

The data can be retrieved between 29/04/2013 (oldest date available) and now for the daily value of BTC (USD, but this is highly tunable).
The resulting dataframe consists of the timestamp, open, close, low and high values.

### bitstamp_USD_1H_30062020_30112020.csv

source: https://bitcoincharts.com/  
This dataset has been made in order to provide a slightly better resolution (hourly) than the one on coinmarketcap.com (daily).  
Hourly BTC values (USD) from https://www.bitstamp.net between 30/06/2020 and 26/11/2020 (to be updated regularly).  
Columns:  
__Timestamp:__ YYYY-mm-dd HH:00:00 format.  
__Open:__ First trade price.  
__High:__  Highest trade price.  
__Low:__  Lowest trade price.  
__Close:__ Last trade price.  
__Volume (BTC):__ Trade volume in Bitcoins.   
__Volume (Currency):__ Trade volume in market's currency (USD here).  
__Weighted price:__ Weighted Bitcoin price. 
