# 🏠 Nashik House Price Prediction

A machine learning project focused on predicting house prices in Nashik, India, using historical housing data. This project demonstrates core competencies in **data preprocessing**, **feature engineering**, **model building**, and **insight generation**, making it a valuable addition to a **data engineering** or **data analytics** portfolio.

---

## 🔍 Project Overview

The real estate market is data-rich and ideal for applying predictive models to estimate property prices. This project aims to:
- Analyze and clean housing data from Nashik
- Build regression models to predict house prices
- Visualize trends and feature importance
- Derive insights that can assist buyers, sellers, and investors

---

## 🧰 Tools & Technologies

- **Python**
  - `Pandas`, `NumPy` for data manipulation
  - `Matplotlib`, `Seaborn` for data visualization
  - `Scikit-learn` for modeling
- **Jupyter Notebook** for interactive development
- **Machine Learning Models**: Linear Regression, Random Forest Regressor

---

## 🗂️ Dataset Summary

- Features: Area (sqft), Location, Number of Bedrooms, Bathrooms, Parking, Amenities, etc.
- Target: House Price in INR
- Data Source: Real estate listings scraped from property websites

---

## 🧹 Data Preprocessing & Feature Engineering

- Handled missing values using statistical imputation
- Encoded categorical variables (e.g., location)
- Removed outliers using IQR method
- Created derived features (e.g., price per square foot)
- Normalized numerical features for consistent scaling

---

## 📊 Exploratory Data Analysis (EDA)

Key insights from EDA:
- Properties in premium locations like Gangapur Road and College Road show significantly higher average prices
- House area and number of bedrooms have strong correlation with price
- Scatter plots and box plots helped visualize distribution and outliers

---

## 🤖 Model Building & Evaluation

| Model                   | R² Score | RMSE        |
|------------------------|----------|-------------|
| Linear Regression      | 0.78     | ₹5.2 Lakh    |
| Random Forest Regressor| **0.85** | **₹3.9 Lakh** |

- **Random Forest** outperformed Linear Regression due to its ability to handle non-linear relationships
- Used `train_test_split` for evaluation and `GridSearchCV` for hyperparameter tuning

---

## 📌 Results & Insights

- **Location**, **area**, and **number of rooms** are the top three factors influencing house prices
- The model can help estimate fair market value, prevent overpaying, and support real estate investment decisions
- Suitable for scaling into a full-stack solution (e.g., with Streamlit frontend or Flask API)

---

## 🚀 Future Enhancements

- Integrate live real estate listings using web scraping or APIs
- Add geo-spatial analysis using folium or geopandas
- Deploy as a web app using Streamlit or Flask
- Move preprocessing and model inference to a pipeline (e.g., with MLflow or Airflow)

---
