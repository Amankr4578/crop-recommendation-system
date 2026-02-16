🌱 Crop Recommendation System 📌 Overview

The Crop Recommendation System predicts the most suitable crop for cultivation based on soil and climatic parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall.

This project applies Data Science, Machine Learning, and Deep Learning techniques to analyze agricultural data and provide actionable insights to farmers, enabling data-driven decision-making.

⚡ Features

Data Cleaning (handling nulls, duplicates, outliers using IQR clipping)

Exploratory Data Analysis (EDA) with Seaborn and Matplotlib

Hypothesis Testing (Z-Test, Chi-Square Test, Spearman Correlation, ANOVA)

Machine Learning Models:

Logistic Regression

Naive Bayes

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Bagging, AdaBoost, Gradient Boosting

Deep Learning Model using Keras Sequential API

Final Model: Random Forest Classifier with high accuracy

Crop prediction based on new user input

🛠️ Tech Stack

Python

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras, Statsmodels, Scipy

📊 Dataset

Name: Crop_recommendation.csv

Features:

N (Nitrogen)

P (Phosphorus)

K (Potassium)

Temperature

Humidity

pH

Rainfall

Target: Crop Label (e.g., rice, maize, apple, coffee, etc.)

🔬 Process Workflow

Data Preprocessing

Handle missing values & duplicates

Outlier detection & removal using IQR method

Feature encoding with LabelEncoder

Exploratory Data Analysis

Histograms, Countplots, Scatterplots, Barplots

Average nutrients requirement per crop

Statistical Testing

Z-Test: Rainfall difference (Rice vs Coffee)

Chi-Square Test: Rainfall vs Humidity

Spearman Correlation: Temperature with Humidity & Rainfall

ANOVA: Temperature variation across crops

Model Training

Train/Test Split (70/30)

Multiple ML algorithms evaluated

Deep Learning model with Dense layers

Model Evaluation

Accuracy score

Confusion Matrix

Classification Report

Final Deployment

Random Forest Classifier chosen for deployment

User can input values for N, P, K, temperature, humidity, pH, rainfall → Predicts crop

📈 Results

Random Forest Accuracy: ~98%

Deep Learning Accuracy: ~96%

Final selected model: Random Forest due to robustness and interpretability.
