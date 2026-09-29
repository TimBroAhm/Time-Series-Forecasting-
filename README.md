Restaurant Sales Time-Series Forecasting

Forecasting restaurant sales from historical transaction data using time-series analysis in Python. The project explores sales patterns (trend, seasonality, weekly cycles) and builds forecasting models to predict future demand, supporting better staffing, inventory, and planning decisions.

Repository Contents

File	Description

Restaurant_Sales_Forecasting.ipynb	Main notebook: data loading, cleaning, exploratory analysis, modeling, and evaluation

Restaurant__transactions.xlsx	

Raw restaurant transaction dataset used in the analysis

hell.html	HTML output/page included in the repo

Project Workflow

Data loading: read transaction records from the Excel file.

Preprocessing: parse dates, handle missing values, and aggregate transactions into a regular time series (e.g., daily sales).

Exploratory analysis: visualize trend, seasonality, and anomalies.

Modeling: train forecasting models on historical data.

Evaluation: compare forecasts against held-out data using error metrics (e.g., MAE, RMSE, MAPE).

Forecasting: generate predictions for future periods.


Getting Started

Prerequisites

Python 3.9+

Jupyter Notebook, JupyterLab, or Google Colab

Installation

bash

git clone https://github.com/TimBroAhm/Time-Series-Forecasting-.git

cd Time-Series-Forecasting-

pip install pandas numpy matplotlib seaborn statsmodels scikit-learn openpyxl jupyter

Run

bash

jupyter notebook Restaurant_Sales_Forecasting.ipynb

Or upload the notebook and the .xlsx file to Google Colab and run all cells.

Results
<!-- Add your best model, metrics, and a forecast plot here, e.g.: --> <!-- ![Forecast plot](images/forecast.png) -->

Model	MAE	RMSE	MAPE

Model 1	–	–	–

Model 2	–	–	–

Tech Stack

Python · Pandas · NumPy · Matplotlib · Statsmodels · Scikit-learn · Jupyter

Future Work

Add external features (holidays, weather, promotions)

Try deep learning models (LSTM, Temporal Fusion Transformer)

Deploy a simple dashboard for interactive forecasts

Author

Tim (@TimBroAhm)

