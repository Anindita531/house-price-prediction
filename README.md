# 🏠 House Price Prediction System (Machine Learning)

## 📌 Overview
This project is a machine learning model that predicts house prices based on property features such as area, location, number of bedrooms, and other housing attributes. The model is trained on real-world real estate data and uses regression algorithms to estimate property prices.

---

## 🎯 Objective
- Build a regression model to predict house prices
- Analyze real estate data for meaningful patterns
- Apply feature engineering and preprocessing
- Evaluate model performance using R² score

---

## 📂 Dataset Description
The dataset contains real estate property details such as:

- Square Foot Area
- Number of BHK
- Property Location (Latitude, Longitude)
- RERA status
- Construction status
- Ready to move / resale information
- Target variable: Price (in Lacs)

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- XGBoost / Random Forest
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧠 Machine Learning Workflow

### 1. Data Preprocessing
- Handled missing values
- Converted categorical features
- Removed irrelevant columns
- Encoded necessary features

### 2. Feature Engineering
- Selected important numerical features
- Removed noisy or high-cardinality features
- Used location-based features (Latitude, Longitude)

### 3. Model Training
- Applied Random Forest / XGBoost Regressor
- Split dataset into training and testing (80:20)
- Trained model on training data

### 4. Model Evaluation
- Used R² Score as evaluation metric
- Checked for overfitting

---

## 📊 Model Performance

| Metric | Score |
|--------|------|
| Train R² | 0.97 |
| Test R² | 0.74 |

---

## 🧪 Sample Prediction

### Input:
- Square Foot: 1300
- BHK: 2
- Location: Bangalore (Lat: 12.97, Lon: 77.59)
- Under Construction: No
- RERA: No
- Ready to Move: Yes
- Resale: Yes

### Output: