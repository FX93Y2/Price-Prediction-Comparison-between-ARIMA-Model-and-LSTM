# Stock Performance Analysis in Relation to R&D Investment

This repository contains a data analysis project that examines the relationship between Research and Development (R&D) spending and stock performance for major companies in the technology and utilities sectors. The primary focus is on comparing the R&D spending's impact on stock prices of Microsoft (MSFT) and Nvidia (NVDA) with an observational contrast to utility companies like Duke Energy (DUK) and The Southern Company (SO).

## Project Overview

The project aims to identify any correlations between the amounts invested in R&D and the stock price fluctuations over a given period. It hypothesizes that increased R&D spending is a sign of a company's potential for innovation, growth, and future earnings, which might be reflected in the stock's performance.

## Repository Structure

- `notebooks/`: Jupyter notebooks with the analysis steps, including data cleaning, exploratory data analysis, visualization, and statistical modeling.
- `src/`: Source code for custom Python functions or classes used in the notebooks.
- `reports/`: Generated reports and summaries of the analysis.
- `images/`: Images and plots generated from the analysis for use in documentation or reports.
- `requirements.txt`: A list of Python packages required to run the notebooks.

## Datasets

The stock price data is sourced from Yahoo Finance using the `yfinance` API, and the R&D spending data is manually curated from company annual reports and trusted financial databases.

## Tools and Technologies

- Python 3.8+
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Statsmodels for statistical analysis
- Jupyter for interactive notebooks

## Getting Started

To get started with this project, clone the repository and install the required Python packages:

```sh
git clone https://github.com/Fy981006/Price-Prediction-Comparison-between-ARIMA-Model-and-LSTM.git
cd Price-Prediction-Comparison-between-ARIMA-Model-and-LSTM
pip install -r requirements.txt
