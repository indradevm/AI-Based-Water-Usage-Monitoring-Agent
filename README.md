AI-Based-Water-Usage-Monitoring-Agent

This project implements an AI-based system to monitor water consumption, detect abnormal usage patterns, forecast future usage, and generate alerts. The system is designed to support water conservation and efficient resource management.

Objectives
Detect abnormal water consumption (anomalies)
Forecast future water usage
Generate alerts for unusual or high consumption
Provide visual insights and analysis

Project Structure
water-usage-ai/
│
├── data/
│   ├── cleaned_daily_water_consumption.csv
│   ├── feature_engineered_data.csv
│   └── alert_results.csv
│
├── notebooks/
│   ├── 1_data_preprocessing.ipynb
│   ├── 2_feature_engineering.ipynb
│   ├── 3_anomaly_detection.ipynb
│   ├── 4_forecasting.ipynb
│   ├── 5_visualization_analysis.ipynb
│
├── README.md

Execution Order 
Run the notebooks in the following order:

1_data_preprocessing.ipynb
2_feature_engineering.ipynb
3_anomaly_detection.ipynb
4_forecasting.ipynb
5_visualization_analysis.ipynb

Software Environment
Python Version
Python 3.10 or above


Required Libraries
Library	Version 
pandas	>= 1.5
numpy	>= 1.23
matplotlib	>= 3.6
seaborn	>= 0.12
scikit-learn	>= 1.2
