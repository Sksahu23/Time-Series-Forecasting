# Time Series Analysis on PJME Energy Usage
This repository contains a project focused on time series analysis of energy usage data from the PJM Interconnection. The goal is to explore, visualize, and forecast energy consumption using various data science techniques, including advanced machine learning models.

## Project Structure
1. Data Loading and Preprocessing:
    - The dataset (PJME_hourly.csv) is loaded and prepared for analysis. The 'Datetime' column is set as the index to facilitate time series operations.

2. Data Exploration and Visualization:
    - Initial visualizations are generated to understand the trends and patterns in the energy usage data.

3. Modeling and Forecasting:
    - Multiple models are employed to forecast future energy usage:

        - **XGBoost**: A tree-based model used for initial forecasting and evaluation.
        - **LSTM** (Long Short-Term Memory): A deep learning model specifically designed to handle sequential data, capturing long-term dependencies in the time series.
        - **Prophet**: A model developed by Facebook, useful for capturing seasonality and trends in time series data with minimal tuning.
-The performance of these models is evaluated using metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- TensorFlow (for LSTM)
- Prophet
- Usage

## Results and Insights
The analysis provides insights into the trends and seasonal patterns of energy usage. The LSTM and Prophet models, in particular, offer robust forecasting capabilities that can assist in planning and optimizing energy resources.
