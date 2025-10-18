# SMOTE-Enhanced Machine Learning Models for Crop Prediction
This project presents a robust machine learning framework for crop recommendation tailored to specific soil and environmental conditions. The core challenge addressed is the significant class imbalance often found in agricultural datasets, where certain crops are far more represented than others, leading to biased and inaccurate models.

This repository demonstrates a complete workflow, from initial Exploratory Data Analysis (EDA) to building and evaluating multiple classifiers. We showcase the transformative impact of the Synthetic Minority Over-sampling Technique (SMOTE) in creating a high-performing prediction model. The final model, a Random Forest classifier trained on SMOTE-balanced data, achieves an accuracy of 86%.

Problem Statement
Traditional crop recommendation models often fail in real-world scenarios due to imbalanced datasets. When a model is trained on data where some crops appear infrequently, it becomes biased towards predicting the majority crops, rendering it unreliable for agricultural planning. This project aims to solve this by implementing a strategy to counteract class imbalance, thereby developing a fair and accurate crop prediction system.The model is trained on a comprehensive crop recommendation dataset. 

The features include:
Soil Nutrients: Nitrogen (N), Phosphorus (P), Potassium (K)
Environmental Factors: Temperature, Humidity, pH, Rainfall

The target variable is the recommended crop , making this a multi-class classification problem. The original dataset exhibits a significant imbalance in the representation of these crop classes.
