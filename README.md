# Traffic Time-Series Analysis

A Jupyter Notebook for exploring and forecasting traffic volume from historical daily observations.

## What is included

- Exploratory analysis and visualization of traffic volume
- Seasonal decomposition and anomaly identification
- Holiday and calendar-effect features
- Stationarity checks with ADF testing
- Autocorrelation analysis with ACF and PACF plots
- Forecasting with Prophet, ARIMA, and SARIMAX
- Model evaluation using regression and time-series metrics

## Project files

- `Traffic.ipynb` - analysis, visualizations, forecasting models, and saved outputs
- `traffic.csv` - expected input data file; provide this locally before running the notebook

## Requirements

Python 3.9 or newer is recommended. Install the notebook dependencies with:

```bash
pip install jupyter pandas numpy matplotlib seaborn statsmodels scikit-learn holidays prophet pmdarima tabulate tqdm
```

## Running the notebook

1. Place `traffic.csv` in this directory.
2. Start Jupyter:

   ```bash
   jupyter notebook
   ```

3. Open `Traffic.ipynb` and run the cells from top to bottom.

The notebook expects a date/time column and a traffic-volume target column. Update the data-loading and column-selection cells if your CSV uses different column names.
