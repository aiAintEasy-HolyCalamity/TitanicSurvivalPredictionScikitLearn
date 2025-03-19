# TitanicSurvivalPredictionScikitLearn
This project leverages the Titanic dataset to build a machine learning model that predicts passenger survival based on various features. The model is created using Scikit-learn, following a structured and efficient pipeline.

Key Steps:
Dependency Installation: Uses libraries like numpy, pandas, scikit-learn, matplotlib, and seaborn.
Data Loading: Retrieves the Titanic dataset from an online source.
Data Preprocessing:
Handles missing values by filling them with median or mode values.
Encodes categorical variables using one-hot encoding.
Drops irrelevant columns such as Name, Ticket, Cabin, and PassengerId.
Exploratory Data Analysis (EDA):
Visualizes data distribution and relationships using histograms, count plots, and heatmaps.
Analyzes correlations and examines factors impacting survival.
Feature Engineering:
Prepares features and target variables.
Splits data into training and testing sets with an 80-20 ratio.
Model Training:
Uses a Random Forest Classifier to train the model on the prepared data.
Model Evaluation:
Measures model performance using accuracy, classification reports, and confusion matrices.
Visualizes the confusion matrix as a heatmap for clarity.
Highlights:
The project demonstrates practical skills in data cleaning, visualization, feature engineering, and model evaluation.
Visual representations, including survival counts and correlation heatmaps, enhance interpretability.
Uses a robust classification model (Random Forest) to predict survival outcomes with high accuracy.
