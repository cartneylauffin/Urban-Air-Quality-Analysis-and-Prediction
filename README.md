# Urban-Air-Quality-Analysis-and-Prediction
This project focuses on the analysis and prediction of urban air quality using real-time environmental data from the OpenAQ API. The work is divided into two key phases: Exploratory Data Analysis and Predictive Modeling, centered around air pollution levels in New Delhi — one of the world’s most polluted cities.

🟢 Phase 1: urban-air-quality-eda

Title: Real-time Air Quality Analysis for Urban Health Monitoring
Description:
This project performs a comprehensive Exploratory Data Analysis (EDA) on real-time air quality data for New Delhi using the OpenAQ API. It focuses on identifying spatial and temporal pollution patterns, investigating relationships between pollutants and weather, and visualizing trends and anomalies to support public health decision-making.

Key Features:
	•	Automated data fetching from OpenAQ API (multiple stations & pollutants)
	•	Data cleaning, merging, and timezone handling
	•	Statistical analysis (mean, std, skewness, etc.) and outlier detection
	•	Visualizations: Time series, box plots, heatmaps, spatial maps
	•	Anomaly detection using statistical thresholds

Technologies: Python, Pandas, NumPy, Seaborn, Matplotlib, Plotly, requests, OpenAQ API

⸻

🔵 Phase 2: air-quality-prediction-ml

Title: Predictive Modeling of Urban Air Quality (PM2.5 Forecasting)
Description:
This project focuses on forecasting next-day PM2.5 concentration using traditional machine learning models. The pipeline includes temporal feature engineering, lag and rolling window statistics, model training, hyperparameter tuning, and performance evaluation to support proactive pollution management.

Key Features:
	•	Time-series regression task for PM2.5 prediction
	•	Feature engineering: Date/time extraction, lag features, rolling stats
	•	Model development: Linear Regression, Decision Tree, Random Forest, Gradient Boosting
	•	Hyperparameter tuning using GridSearchCV & TimeSeriesSplit
	•	Evaluation metrics: MAE, RMSE, R² + feature importance analysis

Technologies: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
