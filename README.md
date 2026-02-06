🚗 Car Price Prediction (MSRP) Using Machine Learning
📌 Project Overview

This project focuses on analyzing automotive data and building a machine learning model to predict car prices (MSRP) based on technical specifications, performance features, and categorical vehicle attributes.

The workflow includes data cleaning, preprocessing, exploratory data analysis (EDA), feature selection, feature engineering, encoding of categorical variables, and model training using Linear Regression.

The objective is to transform raw vehicle data into a structured predictive system capable of estimating car prices accurately.

📂 Dataset Description

The dataset contains structured information about vehicles, including:

Manufacturer and brand information

Vehicle specifications

Engine characteristics

Fuel type

Transmission and drivetrain

Vehicle size and style

Performance metrics

Popularity indicators

MSRP (target variable)

🧹 Data Preprocessing
✔ Data Cleaning

Standardized column names (lowercase + underscore formatting)

Text normalization for categorical features

Removal of high-null columns

Handling missing values

Removal of invalid records

Dropping logically incorrect values (e.g. zero engine cylinders)

✔ Outlier Handling

MSRP outlier filtering (< 1,000,000)

Engine horsepower clipping

Removal of unrealistic values

Distribution smoothing

📊 Exploratory Data Analysis (EDA)

The project includes:

Correlation heatmaps

Feature-to-price relationship analysis

Distribution analysis

Outlier visualization

Feature importance inspection

Statistical summaries

Numeric and categorical relationship analysis

🧠 Feature Engineering
Numerical Features

Selected based on correlation strength and relevance:

year

engine_hp

engine_cylinders

highway_mpg

city_mpg

popularity

number_of_doors

Categorical Feature Processing

Dropped high-cardinality features (e.g. model)

One-Hot Encoding applied to:

make

vehicle_style

vehicle_size

driven_wheels

transmission_type

engine_fuel_type

🤖 Machine Learning Model
Model Used

Linear Regression

Training Pipeline

Feature selection

Categorical encoding

Dataset transformation

Model fitting

Performance evaluation

Model Performance

R² Score: 0.8675
This indicates a strong predictive performance and a high level of explained variance in MSRP.

🎯 Project Objectives

Predict car prices accurately

Identify key price-driving features

Build a scalable ML pricing model

Create a clean ML pipeline

Support data-driven automotive pricing systems

Prepare data for advanced ML models

🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

🚀 Future Improvements

Try advanced models (Random Forest, XGBoost, Gradient Boosting)

Add cross-validation

Hyperparameter tuning

Feature importance analysis

Model explainability (SHAP / LIME)

Web deployment (Flask / FastAPI / Streamlit)

Real-time prediction API

Deep learning price models


👩‍💻 Author

Shereen Alaa
Machine Learning Engineer

GitHub: https://github.com/shreenalaa

LinkedIn: https://www.linkedin.com/in/shreen-alaa/
