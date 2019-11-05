# Solar generation and demand Italy 2015-2016
## Two-years hourly-recorded data of solar power generation and electricity demand
https://www.kaggle.com/arielcedola/solar-generation-and-demand-italy-20152016

# Context

This dataset summarizes valuable data about recent total solar power generation and total electricity demand in a specific european country like Italy. Data are time series with hourly resolution, and values represent average of real-time power (generated and used) per market time unit (*). Data correspond to years 2015 and 2016. They are useful to analyze, for instance, the variation of solar generation with time in the four seasons of the year, the change of electricity demand depending on the day of the week, or in summer/winter holidays. Use of historical weather data could help to visualize the variation of solar power generation with climate conditions, extremely useful excercise for solar power generation forecasting. Studies of load forecasting could be also conducted by making use of the present dataset.

(*) Detailed data descriptions

# Content

The two files include time series data of solar generation and total electricity consumption in Italy during the years 2015 and 2016, with hourly resolution. CSV files are structured in three columns: 1. Date and Time 2. Load 3. Solar Generation The time is expressed in Coordinated Universal Time (UTC), and the format of Date and Time is "%Y-%m-%dT%H%M%SZ". Solar generation and load are floating point numbers, which represent power expressed in MW (Mega Watts) units. Solar generation is the total solar power generated in Italy in 2015 and 2016, calculated by adding the generation in the different italian bidding zones (6 geographical regions: Nord, Centro Nord, Centro Sud, Sud, Sardegna and Sicilia, and 4 poles: Brindisi, Foggia, Priolo and Rossano). Load represents the total demand of power in the same periods. Note: the 2015 file presents a few missing data.

# Acknowledgements

Data has been extracted from "Open Power System Data. 2017. Data Package Time series. Version 2017-07-09 (https://data.open-power-system-data.org/time_series/2017-07-09)."

The primary data source is ENTSO-E Transparency, the central data platform of the European transmission system operators (https://transparency.entsoe.eu).

# Inspiration

Do you think we could improve the Day-ahead load forecasting? Navigate for instance the ENTSO-E Transparency website, it shows up-to-date comparisons between Day ahead total load forecast and Actual total load, by bidding zones or countries. As you will see, sometimes the differences may be significant.

Important: The ENTSO-E Platform is a great repository of energy data. Measured data and forecasts are provided to the Platform by the Primary Data Owners (see Terms and Conditions at https://transparency.entsoe.eu).
