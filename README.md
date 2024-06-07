Predicting Italian electricity load based on hystorical data concerning both demand and weather (temperature) retrieved using two different APIs.
The forecast is based on a standard XGBoost model trained on the whole time series (from 2021-01-01) prior the day/days to forecast.
In case of multiple days to forecast, the new prediction is not added to the following round of forecast.

## OpenMeteo API: 
https://open-meteo.com/en/docs/historical-weather-api
## TERNA API catalog: 
https://developer.terna.it/#en
