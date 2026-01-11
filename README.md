📊 Google Play Store Apps – Data Analysis & Rating Prediction

📌 Project Overview

This project focuses on analyzing Google Play Store application data to understand market trends, user behavior, and factors affecting app success. It also includes a Machine Learning model to predict app ratings based on key attributes such as reviews, installs, size, and price.

The project demonstrates the complete Data Analytics + Data Science workflow, including data cleaning, exploratory data analysis (EDA), visualization, and machine learning.

🎯 Objectives

Perform Exploratory Data Analysis (EDA) on Google Play Store apps

Clean and preprocess real-world noisy data

Analyze relationships between ratings, reviews, installs, price, and size

Identify top-performing app categories

Build a Machine Learning model to predict app ratings

Generate business insights useful for app developers

🧾 Dataset Description

The dataset contains information about apps available on the Google Play Store.

Key Columns:

App – Application name

Category – App category

Rating – User rating (1–5)

Reviews – Number of user reviews

Size – App size

Installs – Number of installs

Type – Free or Paid

Price – App price

Content Rating – Target audience

Genres – App genre

Dataset Size: 10,000+ apps

🛠 Tools & Technologies

Language: Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Environment: Jupyter Notebook / Google Colab

🔄 Project Workflow

Data Loading

Data Cleaning & Preprocessing

Handling Missing Values

Feature Engineering

Exploratory Data Analysis (EDA)

Data Visualization

Machine Learning Model (Linear Regression)

Model Evaluation

Business Insights & Conclusion

🤖 Machine Learning Model

Problem Type: Regression

Target Variable: App Rating

Model Used: Linear Regression

Evaluation Metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

The model shows that Reviews and Installs are the most influential features for predicting app ratings.

📈 Key Insights

GAME and COMMUNICATION categories dominate installs

Higher installs generally lead to more reviews

Price has minimal impact on app rating

Most apps have ratings between 4.0 – 4.5

User engagement is crucial for app success

🚀 How to Run the Project

Clone or download the repository

Open Jupyter Notebook / Google Colab

Upload the dataset files

Run the notebook cells step-by-step

📌 Future Scope

Sentiment analysis on user reviews

Predicting app installs instead of ratings

Time-series analysis based on updates

Model deployment using Flask or Streamlit
