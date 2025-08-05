# 📈 Traffic Forecasting for Istanbul Using Several ML Methods

Forecasting Istanbul traffic using time series and machine learning models. Public dataset from İBB Tech Istanbul Open Data Portal. This project is not affiliated with Istanbul Metropolitan Municipality. The dataset includes historical daily traffic index values, and also  minimum, maximum, and average traffic congestion levels. The main goal here is to accurately predict traffic trends and compare their performance using different forecasting methods based on evaluation metrics.

    Disclaimer: This project is not affiliated with or endorsed by the Istanbul Metropolitan Municipality (İBB) or any of its subsidiaries. The dataset used is publicly available and sourced from the İBB Tech Istanbul Open Data Portal.

📦 **Dataset Overview**

The dataset contains 3,332 daily records with the following columns:

    trafficindexdate: Date of observation (in UTC format)

    minimum_traffic_index: Daily minimum traffic index (integer)

    maximum_traffic_index: Daily maximum traffic index (integer)

    average_traffic_index: Daily average traffic index (float)
    
The traffic data used in this project is obtained from the İBB Tech Istanbul Open Data Portal:
https://data.ibb.gov.tr

🔍 **Objectives**

    Predict traffic congestion patterns and traffic flow for selected areas in Istanbul.

    Evaluate and compare different forecasting models using standard accuracy metrics.

    Provide a reproducible pipeline for traffic data preprocessing, modeling, and performance analysis.

⚙️ **Methods Used**

This project includes but is not limited to:

    Time Series Models: ARIMA, SARIMA, Prophet, Holt-Winters

    Machine Learning Models: Random Forest, Gradient Boosting, Support Vector Regression

    Deep Learning Models: LSTM, GRU, and potentially Temporal Fusion Transformers (TFT)

    Hybrid Models: Ensemble combinations of traditional and deep learning models

📊 **Evaluation Metrics**

Models are compared based on:

    Mean Absolute Error (MAE)

    Root Mean Squared Error (RMSE)

    Mean Absolute Percentage Error (MAPE)

    R² Score


🚧 **Project Status**

Data preprocessing pipeline

Baseline model implementation

Evaluation and comparison of models

Visualization of forecasts
