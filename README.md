# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning techniques. The model is trained on a housing dataset containing various property features such as living area, bedrooms, bathrooms, lot size, location, and construction year.

The objective is to estimate the selling price of a house accurately using regression algorithms.

---

# 🎯 Objectives

- Load and understand the dataset
- Perform data preprocessing
- Handle missing values and duplicate records
- Encode categorical variables
- Perform Exploratory Data Analysis (EDA)
- Train Machine Learning models
- Compare model performance
- Predict house prices
- Save the trained model

---

# 📂 Dataset

The dataset contains the following important features:

- Date
- Bedrooms
- Bathrooms
- Square Feet Living
- Square Feet Lot
- Floors
- Waterfront
- View
- Condition
- Square Feet Above
- Square Feet Basement
- Year Built
- Year Renovated
- Street
- City
- StateZip
- Country

Target Variable:

Price

---

# 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

# 📊 Exploratory Data Analysis (EDA)

The following visualizations were created:

- Correlation Heatmap
- Histograms
- Boxplots
- Scatter Plots
- Pair Plot
- Distribution Plot
- Feature Importance Plot
- Actual vs Predicted Plot
- Residual Plot

---

# 🤖 Machine Learning Models

Two regression algorithms were implemented.

## 1. Linear Regression

Used as the baseline regression model.

## 2. Gradient Boosting Regressor

Used to improve prediction accuracy.

---

# 📈 Evaluation Metrics

The following metrics were used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📁 Project Structure

House-Price-Prediction/

│

├── data.csv

├── HousePricePrediction.ipynb

├── HousePricePredictionModel.pkl

├── Scaler.pkl

├── README.md

└── requirements.txt

---

# ▶ How to Run

1. Open Google Colab

2. Upload the notebook

3. Upload data.csv

4. Run all cells

5. Model will be trained automatically

6. House prices will be predicted

---

# 📊 Results

Both Linear Regression and Gradient Boosting models were trained.

Gradient Boosting achieved better performance with lower error values and higher R² score compared to Linear Regression.

Therefore, Gradient Boosting was selected as the final prediction model.

---

# 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Random Forest Regressor
- XGBoost Regressor
- LightGBM
- Feature Engineering
- Outlier Removal
- Model Deployment using Streamlit or Flask

---

# 👩‍💻 Author

Zainab

AI/ML Engineering Internship

DevelopersHub Corporation
