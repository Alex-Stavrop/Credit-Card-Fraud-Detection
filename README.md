# Credit Card Fraud Detection

## Overview
This project aims to detect potentially fraudulent credit card transactions for Company ABC using a dataset containing transaction details and credit card information. We employ exploratory data analysis, feature engineering, and the Isolation Forest anomaly detection algorithm.

## Dataset
The data consists of two main files:

1. `transactions.csv` - Contains details of credit card transactions, including the date, transaction amount, and location.
2. `cc_info.csv` - Contains general credit card information, including the card limit and zip code.

## Methodology
1. **Exploratory Data Analysis (EDA)**: Analyzed distributions, patterns, and relationships in the data.
2. **Feature Engineering**: Derived several features, including day of the week, hour of the day, and the ratio of transaction amount to credit limit.
3. **Anomaly Detection**: Used the Isolation Forest algorithm to detect potential fraudulent transactions based on the engineered features.

## Visualizations
- Distribution of transaction amounts and credit card limits.
- Time-series plot showing transaction trends.
- Interactive map displaying transaction locations.

## Results
The model flags certain transactions as potential frauds, which are visualized on a map and through a time-series plot. Key statistics about these anomalies are also provided.

## Getting Started
1. Clone this repository.
2. Ensure you have the necessary Python packages installed, including pandas, numpy, matplotlib, seaborn, sklearn, and folium.
3. Run the Jupyter Notebook to see the analysis and results.
