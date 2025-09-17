# 🏠 House Price Prediction – Machine Learning Project

Predict house prices using Machine Learning with Python. This project includes data preprocessing, feature engineering, model building, evaluation, and a Flask web app for real-time predictions.

# 🔍 Overview

The House Price Prediction project is a Machine Learning system that predicts property prices based on features like location, area, number of bedrooms, etc. Using regression models and data analysis techniques, it provides accurate price estimates, helping buyers, sellers, and real estate analysts make data-driven decisions.

# 🎯 Objectives

Predict house prices using machine learning models

Perform data preprocessing and feature engineering for better accuracy

Evaluate multiple regression models to select the best-performing model

Deploy a Flask web app for interactive predictions

# 📊 Features

🏠 Regression Models – Linear Regression, Random Forest, and more

🔄 Data Preprocessing – Handles missing values, categorical encoding, and scaling

📈 Evaluation Metrics – Measures model performance using RMSE, MAE, and R² score

💻 Interactive Web App – Predict house prices in real-time via Flask

📊 Visualization Tools – Graphs for EDA, feature importance, and model predictions

# 🛠️ Tech Stack

Machine Learning: Scikit-learn, XGBoost

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Web App: Flask

Deployment: Heroku / Local Server

Model Storage: Pickle (.pickle)

# 📂 Project Structure
house-price-prediction-machine-learning/
│

├── data/                  → CSV datasets (House_Data.csv, Jalgaon.csv)

├── notebooks/             → Jupyter notebook experiments (house-price-prediction-model.ipynb)

├── model/                 → Trained ML model (home_prices_model.pickle)

├── app/                   → Flask app files (app.py, columns.json)

├── requirements.txt       → Project dependencies

├── README.md              → Project documentation

├── Procfile               → Deployment config (Heroku)

└── .gitignore             → Ignored files (venv, .DS_Store)


# ⚙️ How to Run

1️⃣ Activate Virtual Environment

source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows


2️⃣ Install Dependencies

pip install -r requirements.txt


3️⃣ Run the Flask Web App

python app/app.py


4️⃣ Optional: Open Jupyter Notebook for experiments

jupyter notebook notebooks/house-price-prediction-model.ipynb


# 💡 Tip: Always activate your virtual environment before running scripts to avoid dependency issues.

# 📁 Dataset Info

House_Data.csv – Contains property features and prices

Jalgaon.csv – Local housing data for regional analysis

Features include area, bedrooms, bathrooms, location, and more

# 🌍 Applications

Real estate price estimation

Data-driven decision making for buyers and sellers

Portfolio for showcasing ML skills and deployment

Educational purpose for learning regression and Flask app deployment

# 📌 Results

✅ Predictive models trained and evaluated for accuracy
✅ Interactive Flask app for real-time house price prediction
✅ Visualizations for data exploration and model interpretation

# ✨ Final Thoughts

The House Price Prediction project demonstrates how Machine Learning and Python can provide actionable insights in the real estate domain. By automating price estimation, it reduces manual effort and improves decision-making for stakeholders.

 🏡 “Predicting house prices intelligently — making real estate decisions smarter and easier.”
