
Ad Sale Prediction: 
This project predicts whether a user will purchase a product after clicking on an online advertisement. The model uses user data to classify potential buyers from non-buyers, which can help optimize advertising campaign spending.

Problem Statement:
The goal is to build a machine learning model to solve a binary classification problem: will a user who clicks on an ad make a purchase?
1: The user will purchase the product.
0: The user will not purchase the product.

Dataset:
The dataset was sourced from "/content/DigitalAd_dataset.csv" and contains user demographics and online behavior metrics.

Key features include:
Age: The user's age in years.
Area Income or salary: Average income of the user's geographical area.
Ad Topic Line: The headline of the advertisement.
Clicked on Ad: The target variable (0 or 1).

Technologies & Libraries:
Language: Python
Data Science Libraries: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn
Development Environment: Google Colab

 Project Workflow:
Data Exploration: Loaded the dataset and checked for missing values, data types, and basic statistics.
Exploratory Data Analysis (EDA): Visualized data to understand feature distributions and correlations with the target variable.

Data Preprocessing:
Scaled numerical features using StandardScaler.

Model Building: Split the data into training (80%) and testing (20%) sets and trained several classification models, including  models  used Logistic Regression.

Model Evaluation: Assessed model performance using metrics like Accuracy using Confusion martrix.

Results:
The  Best Performing Model, Logistic Regression model performed best.

Accuracy: 80%

These results show the model is highly effective at identifying users likely to make a purchase.

