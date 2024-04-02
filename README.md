# ExchangeRates
# Coding Assessment - Finding Exchange rates from AUD to NZD for the past 30 days
Date: **30/03/2023**

Version: **1.0**

Environment: **Python 3.11.7 (64-bit)**

**Libraries used:**
* [json](https://docs.python.org/3/library/json.html)
* [urllib.request](https://docs.python.org/3/library/urllib.request.html#module-urllib.request)
* [datetime](https://docs.python.org/3/library/datetime.html)
* [pandas 0.25.0](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
* [Matplotlib Official Documentation)](https://matplotlib.org/3.1.1/api/pyplot_summary.html)
* [warnings](https://docs.python.org/3/library/warnings.html)
* [plotly](https://plotly.com/python/)

##  Introduction
 This assessment is to connect to any exchange rates API ([Exchange Rates API](https://api.apilayer.com/exchangerates_data/timeseries)) to get the exchange rates of Australia (AUD) to Newzeland (NZD) for the past 30 days which is in __json file format__. Also pre-processed the data to avoid any issues.
 
Main task is to perorm the following data analysis.

1. Find the `best` and `worst` exchange rates for that time period
2. Calculate the `average` exchange rate for the month.
    
More details for each task will be given in the following sections.

## Connecting to API to fetch exchange rates and storing the output in Json format

#### Testing Scenario:
We can change the input parameters `number_of_days` to 30/60/90/365 etc for further checks.

Same way we can change `input_currency` & `output_currency` for further checks.

## Pre-Processing data

Data is pre-processed and extracting date & exchange rates separately and stored in a list

## Storing data in Dataframe for further processing
Storing the extracted values in a dataframe and then adding `Day_Of_Week` column to get week name and mapping it to data and then storing it in another dataframe for further analysis.

## Performing null check, shape of data & descriptive statistics

## Finding best and worst exchange rates and also average exchange rate for the month

## Plotting Current rate for AUD to NZD for past 30 days

On hovering we can see the `Date` & `Exchange Rate`

## Plotting Current rate on day of week basis for AUD to NZD for past 30 days
On hovering we can see the `Day Of Week` & `Exchange Rate`

# Simple Linear Regression

Performed Simple Linear Regression to see future prediction

# Conclusion

To conclude, I had connected to one exchange rates API ([Exchange Rates API](https://api.apilayer.com/exchangerates_data/timeseries)) to get the exchange rates of Australia (AUD) to Newzeland (NZD) for the past 30 days which is in json file format. I also pre-processed the data to avoid any issues and performed the following data analysis.

1. Find the `best` and `worst` exchange rates for that time period
   
2. Calculate the `average` exchange rate for the month.

Also I had observed that the Exchange rates are high on `Fridays` and low on `Mondays`. It is like week is starting on a low-note and ending on a high-note.

# Future Scope

Further prediction analysis can be donw using Time-Series Forecasting models like `ARIMA, SARIMA` etc.

# References
1. API Calls for exchange rates https://apilayer.com/marketplace/exchangerates_data-api#documentation-tab
