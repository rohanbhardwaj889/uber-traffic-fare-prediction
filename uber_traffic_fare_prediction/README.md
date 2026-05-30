# Uber Traffic Fare Prediction & Traffic Forecasting

## Project Overview

This project analyzes the impact of traffic congestion, weather conditions, and special events on Uber fare pricing and traffic patterns. The objective is to identify key factors affecting traffic flow and develop predictive models for traffic forecasting.

The project combines Exploratory Data Analysis (EDA), Feature Engineering, Time Series Forecasting, and Machine Learning techniques to generate actionable insights and improve prediction accuracy.

---

## Business Problem

Traffic congestion significantly affects travel time, ride availability, and dynamic pricing in ride-hailing services such as Uber.

This project aims to:

- Analyze traffic patterns across different time periods.
- Evaluate the influence of weather conditions on traffic volume.
- Measure the impact of special events on congestion.
- Forecast traffic levels using machine learning and deep learning models.
- Identify the most important factors affecting traffic flow.

---

## Dataset

The dataset contains information related to:

- Traffic Volume
- Date and Time
- Weather Conditions
- Event Information
- Junction-Level Traffic Data

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- TensorFlow / Keras
- Statsmodels
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection & Preprocessing

- Data Cleaning
- Handling Missing Values
- Feature Transformation
- Date-Time Processing

### 2. Exploratory Data Analysis

- Traffic Trend Analysis
- Hourly Traffic Distribution
- Weather Impact Analysis
- Event-Based Congestion Analysis
- Correlation Analysis

### 3. Feature Engineering

Created important features such as:

- Weather Severity Index
- Congestion Index
- Time of Day Categories
- Weekend Indicator

### 4. Model Development

The following models were implemented:

- ARIMA
- Random Forest Regressor
- Gradient Boosting Regressor
- LSTM Neural Network

### 5. Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Key Insights

- Traffic volume varies significantly by time of day.
- Weather conditions directly influence congestion levels.
- Special events increase traffic density around affected areas.
- Feature engineering substantially improved predictive performance.
- LSTM achieved the best forecasting performance among tested models.

---

## Project Structure

```text
Uber-Traffic-Fare-Prediction/
│
├── data/
├── notebooks/
├── images/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Results

The project successfully identified major traffic influencing factors and developed predictive models capable of forecasting traffic trends with strong accuracy.

---

## Future Improvements

- Real-time traffic prediction
- Integration with live weather APIs
- Interactive dashboard development using Power BI or Streamlit
- Deployment as a web application

---

## Author

### Rohan Bhardwaj

Aspiring Data Analyst passionate about data analytics, machine learning, and business intelligence.

**Skills:** Python | SQL | Power BI | Tableau | Machine Learning

---

## License

This project is licensed under the MIT License.