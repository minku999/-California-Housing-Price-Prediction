# 🏠 California Housing Price Prediction

This project demonstrates a full machine learning pipeline to predict house prices using the California Housing dataset. The notebook covers data preprocessing, visualization, feature engineering, model training, evaluation, and saving the model.

---

## 📊 Dataset

The dataset used is the **California Housing** dataset, which includes attributes like median income, housing age, rooms per household, population, etc. The target variable is `median_house_value`.

---

## 🔧 Features

- Stratified sampling based on income categories
- Exploratory Data Analysis (EDA) with visualizations
- Feature correlation analysis using heatmaps and scatter plots
- Preprocessing pipelines for numerical and categorical data
- Model training using:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Evaluation using RMSE (Root Mean Squared Error)
- Model persistence using `joblib`

---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 📁 File Structure
├── housing.csv # Dataset (not included in repo)
├── housing_model.ipynb # Jupyter Notebook with full ML pipeline
├── model.pkl # Trained Random Forest model
├── pipeline.pkl # Preprocessing pipeline
└── README.md # This file
Mayank
Aspiring Data Scientist | BCA Student
LinkedIn | GitHub

