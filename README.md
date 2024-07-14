# Forecasting Monthly Household Power Consumption
This project was completed as part of the PGP AI and DS program at Jio Institute in July 2024. The goal was to develop a predictive model that accurately forecasts household electric power consumption using historical data.


## Project Overview
Objective: To create a model that predicts monthly household power consumption, aiding in energy management and planning.


Dataset: The dataset used contains electric power consumption measurements from a single household with a one-minute sampling rate over nearly 4 years. The dataset was sourced from Kaggle.


## Approach
Data Acquisition: Collected data from Kaggle.

Data Preprocessing: Cleaned and prepared the data for analysis.

Exploratory Data Analysis: Analyzed the data to understand underlying patterns and trends.

Time Series Modeling: Built models to forecast future power consumption.

Time Series Cross-Validation: Validated the models to ensure their accuracy.

Residual Diagnostics: Diagnosed residuals to check for any inconsistencies.

Error Reporting: Reported errors to measure model performance.


## Future Scope
Incorporating additional features such as weather data, economic indicators, and social events to enhance forecasting accuracy.

Developing a real-time forecasting system that updates models as new data becomes available.

Scaling the model to handle larger datasets or regional forecasts for more detailed insights.


## Limitations
Data resampling from minutes to months reduced data points, requiring future work on more real-time data or extending the dataset.

Weak relationships between variables suggested limited applicability of multivariate models, requiring further research.

Future work includes using LSTM models for the household dataset.


## Conclusion
This project provided valuable insights into energy consumption patterns and highlighted areas for further research and model improvement. 
