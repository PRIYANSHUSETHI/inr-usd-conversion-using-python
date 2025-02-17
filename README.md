# USD to INR Conversion Rate Prediction

## Overview
This project predicts the USD to INR conversion rate using historical exchange rate data. It involves data preprocessing, visualization, and forecasting using machine learning techniques.

## Dataset
The dataset used contains historical exchange rates between USD and INR. It includes date-wise records of exchange rates, particularly the closing price.

## Technologies Used
- Python
- Pandas, NumPy (Data manipulation and analysis)
- Matplotlib, Seaborn, Plotly (Data visualization)
- Scikit-learn (Machine learning model)

## Project Workflow

### 1. Data Collection & Preprocessing
- Load the dataset using `pandas.read_csv()`.
- Check for missing values and remove any inconsistencies.
- Convert date formats and extract essential features such as year and month.

### 2. Exploratory Data Analysis (EDA)
- Generate summary statistics to understand the dataset.
- Visualize the historical exchange rate trends using line charts.
- Analyze yearly and monthly trends to identify patterns.

### 3. Feature Engineering
- Create new features based on extracted date information.
- Prepare data by splitting it into training and testing sets.

### 4. Model Development & Training
- Select an appropriate regression model for time series forecasting.
- Train the model using the historical exchange rate data.
- Evaluate model performance using RMSE and R² score.

### 5. Prediction & Forecasting
- Use the trained model to predict future exchange rates.
- Compare actual vs predicted values and visualize results.
- Identify potential trends and fluctuations in exchange rates.

### 6. Future Enhancements
- Experiment with advanced models like LSTM or ARIMA for improved accuracy.
- Integrate external economic indicators to enhance predictions.
- Deploy the model as a real-time forecasting tool.

## Results
- The model successfully predicts future exchange rates with reasonable accuracy.
- Data visualizations provide insights into trends and fluctuations over the years.

## Future Improvements
- Improve model accuracy using advanced algorithms like LSTM or ARIMA.
- Incorporate additional economic indicators for better predictions.
- Deploy the model as a web application for real-time forecasting.

## Conclusion
This project showcases the potential of machine learning in predicting exchange rates using historical data. By leveraging regression models and time-series analysis, trends and future exchange rates can be forecasted with reasonable accuracy. Further improvements, such as advanced deep learning models and external economic factors, can enhance the prediction performance and practical applications.
