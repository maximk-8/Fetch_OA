# Receipt Forecasting Model for Fetch Rewards

## Overview
This project contains a machine learning model designed to predict the number of receipts scanned daily into the Fetch Rewards app, which is a key performance indicator (KPI) for the business. The model forecasts the approximate number of scanned receipts for each month of the year 2022 using the provided data for 2021.

## Model Description
The model is an ARIMA (AutoRegressive Integrated Moving Average) time series forecasting model, which is capable of capturing trends, seasonality, and other patterns from historical daily receipt counts.

## Repository Structure
- `Fetch.ipynb`: Jupyter notebook with the entire model development process, including data preprocessing, model training, and forecasting.
- `data_daily.csv`: CSV of the 2021 receipt data.

## How to Run
To run this project, you need to have Python installed on your machine along with the necessary libraries.

1. Clone the repository: `git clone https://maximk-8/Fetch_OA.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook`

## Methodology
The notebook `Fetch.ipynb` contains detailed explanations and comments for each step of the model development process.

## Evaluation
The model's performance was evaluated using cross-validation on the 2021 data, and the best-performing model was selected for the final forecasting.
