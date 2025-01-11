# Sales Analysis and Prediction

## Overview
The `Sales.ipynb` notebook provides a detailed analysis of sales data, combining insights from multiple datasets, and building predictive models. The project includes a deployed Streamlit application for real-time sales prediction and interactive analysis.

## Features
- **Data Loading**: Reads data from multiple sources, including:
  - `train.csv`
  - `stores.csv`
  - `oil.csv`
  - `holidays_events.csv`
  - `transactions.csv`
- **Data Cleaning**: Processes raw data by handling missing values, merging datasets, and preparing features for analysis.
- **Exploratory Data Analysis (EDA)**: Identifies trends and relationships across datasets using visualizations.
- **Predictive Modeling**: Develops machine learning models for forecasting sales based on historical data.
- **Streamlit Deployment**: Deploys a user-friendly web app for real-time predictions.

## Prerequisites
Ensure the following are installed in your Python environment:
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- streamlit

## Usage
### Notebook
1. Clone this repository or download the `Sales.ipynb` notebook.
2. Place the required CSV files (`train.csv`, `stores.csv`, `oil.csv`, `holidays_events.csv`, `transactions.csv`) in the same directory as the notebook.
3. Open the notebook using Jupyter Notebook or any compatible IDE.
4. Run the cells sequentially to perform data analysis and modeling.

### Streamlit Application
1. Run the Streamlit app using the following command:
   ```bash
   streamlit run app.py
   ```
2. Use the web interface to input data and receive sales predictions.

## Datasets
The following datasets are required:
- **Train Dataset (`train.csv`)**: Contains historical sales data.
- **Stores Dataset (`stores.csv`)**: Information about store locations and types.
- **Oil Dataset (`oil.csv`)**: Records of oil prices over time.
- **Holidays Events (`holidays_events.csv`)**: Details about holidays and special events.
- **Transactions Dataset (`transactions.csv`)**: Transaction data from stores.

Ensure these datasets are formatted correctly and aligned with the notebook's preprocessing steps.

## Outputs
The project generates:
- Cleaned and processed datasets.
- Insights and visualizations highlighting sales trends and factors affecting them.
- Predictive model results for sales forecasting.
- An interactive Streamlit web app for real-time predictions.

## Notes
- Customize the notebook and app as needed to suit your specific requirements.
- Ensure dependencies are updated to their latest versions for compatibility.

## Acknowledgments
This project combines data analysis, machine learning, and deployment using Streamlit to deliver a comprehensive solution for sales analysis and prediction.

