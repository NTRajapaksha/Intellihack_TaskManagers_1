# 🌧️ Rainfall Prediction Model for Smart Agriculture
This project focuses on developing a rainfall prediction model to assist farmers in making informed decisions for the next 21 days. The model leverages machine learning techniques to analyze weather patterns and forecast rain probabilities.



📌 Key Features


Exploratory Data Analysis (EDA)


Examined 300+ weather records, including temperature, humidity, wind speed, cloud cover, and pressure.


Identified seasonal patterns, correlations, and class imbalances in the dataset.



*Data Cleaning & Preprocessing*

Handled missing values using time-based interpolation.

Created lagged features and rolling averages to capture temporal dependencies.

Addressed data anomalies (e.g., extreme wind speed fluctuations).

Applied SMOTE oversampling to balance the dataset.

*Model Training & Evaluation*

Tested Random Forest, XGBoost, SVM, and Logistic Regression models.

Logistic Regression achieved the best performance with 72.1% accuracy.

Evaluated models using accuracy, precision, recall, and F1-score.

*Hyperparameter Tuning*


Used GridSearchCV with Stratified K-Fold cross-validation.

Optimized hyperparameters for best model performance.

21-Day Rainfall Probability Forecast

Deployed the Logistic Regression model to predict rain probabilities for future dates.
Forecast values generated using historical trends with added randomness.
