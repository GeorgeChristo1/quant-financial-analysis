# Quant & Financial Analysis

## Project overview

This project uses Python to compare three synthetic stocks and a synthetic market index. It explores how returns and different measures of risk can be used to describe and compare financial assets.

## Tools used

* Python
* pandas
* NumPy
* Matplotlib
* JupyterLab

## Analysis performed

The notebook includes:

* Stock-price and market-index charts
* Daily simple returns and average daily returns
* Daily return volatility
* A three-observation moving average
* Return correlations
* Beta relative to the market index
* Daily Sharpe ratios, assuming a zero risk-free return
* A risk–return chart
* An illustrative portfolio expected-return calculation using `np.dot()`

## Dataset

The project uses 15 observations of **synthetic practice data** for three stocks and a market index. The dates are consecutive calendar days, including weekends. The data does not represent actual market prices.

## Limitations

The dataset is small and synthetic, so the results should not be interpreted as real-world investment findings. The calculated returns, volatility, correlations, beta and Sharpe ratios describe this practice dataset only and do not predict future performance.

## How to run

Open `Phase 4 Project.ipynb` in JupyterLab and run the cells from top to bottom. The notebook uses pandas, NumPy and Matplotlib.
