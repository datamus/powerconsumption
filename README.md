# Overview
This repository contains the analysis and time series forecasting of hourly power consumption data from PJM Interconnection LLC (PJM), a regional transmission organization (RTO) in the United States. The data spans from 2002 to 2018 and includes various features such as hour, day of the week, month, year, and power consumption in megawatts (MW).

## Data Description
The dataset used in this analysis includes the following columns:

- `hour`: Hour of the day (0-23)
- `dayofweek`: Day of the week (0=Monday, 6=Sunday)
- `quarter`: Quarter of the year (1-4)
- `month`: Month of the year (1-12)
- `year`: Year (2002-2018)
- `dayofyear`: Day of the year (1-366)
- `dayofmonth`: Day of the month (1-31)
- `weekofyear`: Week of the year (1-53)
- `PJMW_MW`: Power consumption in megawatts (MW)
- `Season`: Encoded season of the year (0=Winter, 1=Spring, 2=Summer, 3=Autumn)

## Exploratory Data Analysis (EDA)
A thorough EDA was conducted to understand the distribution and trends in the data. Key statistics include:

## Time Series Forecasting
A time series forecasting model was developed using CatBoost, a high-performance gradient boosting library. The model predicts hourly power consumption based on historical data and the various features described above.

## Data Source
The data is sourced from PJM Interconnection LLC's website, covering all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.
