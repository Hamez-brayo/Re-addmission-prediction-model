# Predicting Patient Readmission Risk

This project develops a predictive model for patient readmission risk. By accurately identifying high-risk patients, hospitals and medical providers can better allocate resources and improve patient care, potentially reducing readmission rates and associated costs.

## Project Overview
- **Goal**: Predict the likelihood of patient readmission based on demographics, medical metrics, and hospital visit information.
- **Models Used**: Logistic Regression, Random Forest, Neural Network
- **Accuracy Achieved**: Approximately 0.33 across models, indicating a consistent pattern for predicting readmission.

## Project Structure
1. **Business Understanding**: Defines the project goals, including identifying key factors and addressing hospital management concerns.
2. **Data Understanding**: Describes the data sources, patient attributes, and target variable (`readmitted`).
3. **Data Cleaning**: Details data preparation steps, such as handling missing values and normalizing data.
4. **Exploratory Data Analysis (EDA)**: Visualizes patterns and potential correlations among patient characteristics and readmission rates.
5. **Modeling and Evaluation**: Trains and evaluates three models to predict readmission, providing a robust baseline.
6. **Conclusion**: Summarizes findings, including that each model identifies a 33% chance of readmission.

## Key Features
- **Feature Scaling**: Normalization of features for optimal model performance.
- **Unsupervised Learning (Clustering)**: K-means clustering groups patients with similar characteristics, adding insights into high-risk categories.
- **Supervised Learning**: Logistic Regression, Random Forest, and Neural Network models predict the likelihood of readmission.

