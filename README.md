# COVID-19 Progression & Time Series Forecasting
# Project Description
This project analyzes the global progression of the COVID-19 pandemic using time-series data provided by John Hopkins University. The objective is to visualize historical trends, test for data stationarity, and implement an ARIMA (AutoRegressive Integrated Moving Average) model to forecast future cases and fatalities. This analysis provides critical insights for pandemic-related strategy planning, such as identifying high-growth regions and determining windows for lockdown implementation.

# Student Information
Name: Kgomotso Moses Motlalekgosi

# Team Members:(Individual Project)
Date Completed
March, 2026

# Project Requirements
To run this notebook, you will need Python installed with the following libraries:

pandas (Data manipulation)
matplotlib & seaborn (Visualization)
statsmodels (ARIMA model and Dickey-Fuller test)
numpy (Numerical operations)
scikit-learn (Model evaluation)

# How to Run the Project
Clone the Repository: git clone 
Install Dependencies: pip install pandas matplotlib seaborn statsmodels scikit-learn
Data Setup: Ensure the global confirmed cases and fatalities CSV files are in the root directory.
Execute: Open covid_forecast.ipynb in Jupyter Notebook and run all cells sequentially.

# Key Insights & Objectives
Trend Analysis: Visualization of confirmed cases and fatalities across different NERC-style global regions.
Slope Analysis: Identification of regions where the rate of infection (slope) is highest.
Stationarity Testing: Application of the Augmented Dickey-Fuller (ADF) Test and Rolling Statistics (Mean/Standard Deviation) to prepare data for forecasting.
Forecasting: Using ARIMA to predict the progression window for fatalities and cases.

# Model Evaluation Metrics
Mean Absolute Percentage Error (MAPE): Used to measure the accuracy of the forecast.
Confidence Intervals: Provided to visualize the statistical uncertainty in future projections.

# Acknowledgements & Credits
Data Source: John Hopkins University (JHU) CSSE
Education: EdTech Africa Data Science Program.
