# Rising Star Pre assignment

## Summary

* The web address from which the necessary data is obtained:

  https://www.coingecko.com/en/api/documentation

* Bitcoin data, in euros.

* The data includes date (of the timestamp type), market caps and total volumes variables.

* The aim of this project is to analyze the market value of bitcoin for a given date range.

## Data preparation

* The bitcoin data is obtained from the API by the date range provided by the user.

* Data preprocessing steps were applied.

  * 3 tables(time,market caps,total volumes) are combined and this combination makes the works easier in the upcoming tasks.
  * The date(timestamp format) is converted to time data to make it ready for the analysis.
  * If the date range is between 1-90 days, the data is acquired hourly. Since daily data is used, the closest data to 00:00 UTC time of the day is selected.
  
* Time-dependent changes in prices, market caps and volumes values are visualized.

## Tasks

   A. The daily price data in a certain date range given by the downward_trend function were compared consecutively. It was determined how many days the longest   downtrend was.

   B. The maximum value (the highest trading volume) of the total volumes variable in euros and the date of this value were reached.

   C. By finding the maximum profit the given date range, it was determined on which day the bitcoin should be bought and sold in order to obtain this profit.
