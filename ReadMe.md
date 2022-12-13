# ReadMe

## Google sheet operations 

The following section describes the Google sheet functions that has been used to retrieve stock details.

### Getting the Mastercard share data
```
=GOOGLEFINANCE("MA", "price", DATE(2021,1,1), DATE(2022,12,31), "DAILY") 
```

### Getting the Apple share details 
```
=GOOGLEFINANCE("AAPL", "price", DATE(2018,1,2), DATE(2019,12,31), "DAILY")
```

### Getting the Tesla share prices
```
=GOOGLEFINANCE("TSLA", "price", DATE(2018,1,2), DATE(2019,12,31), "DAILY")
```

