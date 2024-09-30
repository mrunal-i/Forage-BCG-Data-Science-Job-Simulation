# Forage-BCG-Data-Science-Job-Simulation
This project focuses on predicting customer churn for PowerCo, a client of BCG X, by utilizing a Random Forest classification model.

# Objectives
Analyze Price Sensitivity: Investigate if price sensitivity is the most influential factor for customer churn and assess its impact.
Feature Engineering: Engineer new features based on existing data to improve churn prediction, such as off-peak price differences between December and January.
Predictive Modeling: Use a Random Forest classifier to predict customer churn, utilizing engineered features and existing data.

# Concepts
1. Data Science at BCG X
A Data Scientist at BCG X focuses on delivering value to businesses by predicting outcomes based on data, using a combination of:
Statistics and Mathematics: For data analysis.
Programming: For building and testing models.
Communication: To explain insights to clients and stakeholders.
2. Price Sensitivity
Price sensitivity is the degree to which customers' demand for energy consumption changes with price fluctuations. In this project, we explore how price sensitivity influences customer churn.

3. Price Elasticity of Demand
This concept measures the change in customer consumption when prices change. Understanding elasticity helps us model customer behavior based on price changes.

4. Feature Engineering
Feature engineering improves machine learning models by creating new features or modifying existing ones. For example:
Calculating the difference between off-peak prices in December and January for each customer.
Adding, deleting, or transforming variables to make them more relevant for churn prediction.
5. Classification Model
Since churn is a binary outcome (True/False), this project uses a classification model to predict whether a customer will churn. Specifically, the Random Forest classifier was chosen for its ability to handle large datasets and its robustness against overfitting.

6. Random Forest Classifier
A Random Forest is an ensemble learning method that uses multiple decision trees to make predictions. It aggregates results from various trees (based on a majority vote) to predict outcomes such as churn.

# Project Workflow
1. Data Analysis and Price Sensitivity Investigation
Goal: Determine if price sensitivity is the primary driver of churn.
Steps:
Perform exploratory data analysis to understand the relationships between features and churn.
Measure the impact of price sensitivity using relevant metrics like price elasticity.
2. Feature Engineering
Goal: Create new features based on the difference in off-peak prices between December and January to better predict churn.
Steps:
Extract relevant price data.
Calculate and add new feature columns for each customer based on this price difference.
Review data for completeness and accuracy after transformation.
3. Churn Prediction with Random Forest
Goal: Build and test a Random Forest classifier to predict churn.
Steps:
Train the model on historical data with churn labels.
Evaluate its performance using accuracy, precision, recall, and other relevant metrics.
Tune hyperparameters to improve model accuracy and reduce overfitting.

# Tools and Technologies Used
Python: For data analysis, feature engineering, and machine learning.
Pandas: For data manipulation and transformation.
Scikit-learn: For machine learning algorithms, including the Random Forest classifier.
Matplotlib/Seaborn: For data visualization during exploratory analysis.

# Deliverables
Exploratory Data Analysis: A summary of insights gained from analyzing PowerCo’s data with a focus on price sensitivity and churn.
Engineered Features: New columns representing calculated price differences between December and January.
Random Forest Model: A trained classification model to predict customer churn, along with performance evaluation metrics.
