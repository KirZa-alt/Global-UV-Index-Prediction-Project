# Global-UV-Index-Prediction-Project

# 🌐 Global UV Index Prediction

This project predicts the **UV Index (UVI)** based on **geographical and temporal data** using Python. It demonstrates a complete **data science workflow**, including data cleaning, feature engineering, regression modeling, evaluation, and interactive prediction.

---

## 💠 Project Overview

Predicting UVI is crucial for **health, environment, and safety**. This project uses historical global UV data to build models capable of forecasting UVI based on location, time, and other factors.

Key highlights include:

- **Data Cleaning & Preparation:** Handled missing values, removed unrealistic UVI values, processed date and time, extracted features like hour, day, month, and season.  
- **Exploratory Data Analysis (EDA):** Visualized distributions, correlations, and feature relationships via histograms, scatterplots, boxplots, and heatmaps.  
- **Feature Engineering:** Encoded categorical variables (`time_of_day`), mapped months to seasons, applied log and Yeo-Johnson transformations.  
- **Feature Scaling:** StandardScaler and MinMaxScaler applied to numeric features.  
- **Regression Modeling:** Implemented multiple models:
  - Linear Regression  
  - Polynomial Regression (non-linear relationships)  
  - Random Forest Regression (ensemble learning)  
- **Model Evaluation:** Metrics used: **MSE, RMSE, MAE, R²**, along with cross-validation and predicted vs actual plots.  
- **Model Optimization:** Hyperparameter tuning with **GridSearchCV**, feature importance analysis.  
- **Interactive Prediction:** Users can input latitude, longitude, hour, and time of day to get real-time predicted UVI.  

---

## 🛠️ Technologies & Libraries

- **Python**  
- **pandas, numpy** – Data manipulation  
- **matplotlib, seaborn** – Visualization  
- **scikit-learn** – Preprocessing, regression models, pipelines, cross-validation, hyperparameter tuning  

---

## 📂 Dataset

- **Source:** [Global UV Index Dataset on Kaggle](https://www.kaggle.com/gauravkumar2525/global-uv-index-dataset)  
- **File used:** `uv_rays_dataset.csv`  
- **Target Variable:** `uvi`  
- **Features include:** `latitude`, `longitude`, `date`, `time`, `hour`, `time_of_day`, `time_of_day_encoded`, `season`, etc.  

---

## ⚡ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/global-uv-index-prediction.git
