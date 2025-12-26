# Short-Term Temperature Forecasting using ARIMA and LSTM

## Overview
Forecast short-term temperatures for multiple US cities by comparing classical time-series modeling (ARIMA) with deep learning (LSTM) and a weighted hybrid. The work is primarily in R with supporting Python exploration, using a shared temperature dataset.

## Data
- Source file: [US_City_Temp_Data.csv](US_City_Temp_Data.csv) (a copy also lives in [Code/TS analysis/US_City_Temp_Data.csv](Code/TS%20analysis/US_City_Temp_Data.csv)).
- Schema: `time` column plus one column per city (e.g., `albuquerque`); temperatures are numeric and time is parsed as a Date.
- Frequency: treated as monthly in the R workflow (12 periods per year) when building ARIMA models.

## Methods
- ARIMA: stationarity checks (ADF), order selection via `auto.arima`, diagnostics, and 12-step forecasts. Model order is expressed as $(p,d,q)$.
- LSTM: two stacked LSTM layers (50 units each) with a dense output; inputs are scaled and reshaped to a $(n, 1, 1)$ sequence for single-step forecasting.
- Hybrid: convex combination of ARIMA forecasts and unscaled LSTM predictions, with weights derived from relative RMSE to favor the lower-error model; both simple averaging and weighted schemes are implemented.
- Multi-city loop: iterates over every city column, fits ARIMA and LSTM per city, computes RMSEs, and visualizes hybrid performance.

Key R notebook: [Code/TS analysis/Team12Code.Rmd](Code/TS%20analysis/Team12Code.Rmd).
Supporting Python notebook: [Code/PyCode_Stat.ipynb](Code/PyCode_Stat.ipynb).

## Repository Layout
- Data: [US_City_Temp_Data.csv](US_City_Temp_Data.csv)
- R workflow and renders: [Code/TS analysis/](Code/TS%20analysis/)
- Python exploration: [Code/PyCode_Stat.ipynb](Code/PyCode_Stat.ipynb)
- Outputs/examples: HTML renders in [Code/TS analysis/](Code/TS%20analysis/)

## Setup
Python (optional, for the notebook):
```bash
pip install pandas numpy scikit-learn tensorflow statsmodels matplotlib seaborn
```

R packages (used in the Rmd):
```r
install.packages(c("forecast", "tseries", "dplyr", "ggplot2", "keras", "tensorflow", "Metrics", "caret", "gridExtra"))
```

Ensure the working directory contains `US_City_Temp_Data.csv` before running.

## How to Run
R (main analysis):
1) Open [Code/TS analysis/Team12Code.Rmd](Code/TS%20analysis/Team12Code.Rmd) in RStudio.
2) Knit to HTML or run chunks interactively. The default example uses the Albuquerque series; the multi-city section loops through all city columns.

Python (if desired):
1) Open [Code/PyCode_Stat.ipynb](Code/PyCode_Stat.ipynb) in Jupyter or VS Code.
2) Execute the cells to mirror ARIMA/LSTM exploration in Python.

## Outputs and Metrics
- During execution, the R notebook prints RMSE for ARIMA, LSTM, simple hybrid, and weighted hybrid per city.
- Plots compare actuals vs forecasts for each model and summarize hybrid RMSE across cities.
- Record the printed RMSE values in this section after running with your environment and data slice.

## Status
Course project for the University at Buffalo (Team 12, 2024). Additional tuning or result logging can be added based on new runs.
