# Bengaluru House Price Prediction 🏠

A supervised machine learning project to predict housing prices in Bengaluru based on various features such as location, area, number of bedrooms, and bathrooms.
Focusing on Exploratory data analysis (EDA) using Python on large datasets, identifying correlations, handling missing values, managing outliers, encoding techniques, feature selection, model evaluation and visualising insights to improve model accuracy.


## 📌 Problem Statement
In the real estate market, accurately predicting house prices is a challenge due to the dynamic nature of property values influenced by multiple factors such as location, size, and number of rooms. The growing availability of housing data offers an opportunity to apply machine learning techniques to derive insights from past sales data. Buyers and sellers both face difficulty for making decisions as traditional pricing methods are time-consuming and inconsistent. This project aims to estimate the selling price of a house based on its features, using a supervised machine learning model. The objective is to provide a solution that can assist real estate agents, property investors and homeowners.

## 📊 Dataset
- Source: [Kaggle - Bengaluru House Price Data](https://www.kaggle.com/datasets/rishabhr717/bengaluru-house-datacsv)
- Shape: (13320, 9)
- Features: Location, Size, Total Sqft, Bath, Balcony, Price, etc.

## 🧹 Data Preprocessing
- Handling missing values
- Feature engineering (e.g., location simplification)
- Outlier detection and removal
- One-hot encoding of categorical variables

## 🧠 Model Used
- Linear Regression (baseline)
- Train-test split and model evaluation using R² score and MSE

## 🔍 Key Insights
- Clear multicollinearity analysis
- Feature selection improved model performance
- Addressed skewed location data using dimensionality reduction

## 📈 Results
- Mean Squared Error: 4413.675
- R-squared: 0.730196

## 🚀 How to Run
1. Clone this repo
2. Open the `.ipynb` file in Google Colab or Jupyter Notebook
3. Run the cells step-by-step

## 📬 Contact
Anjana Sundar – [LinkedIn](https://www.linkedin.com/in/anjanasundar/) – [anjanasundar19@gmail.com](anjanasundar19@gmail.com)
