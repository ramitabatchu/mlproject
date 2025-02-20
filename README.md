# Student Test Performance Predictor

## Overview
The **Student Test Performance Predictor** is a data-driven project that leverages machine learning techniques to analyze and predict students' test scores based 
on multiple influencing factors. This project provides insights into academic performance, helping educators and students optimize study strategies for better outcomes. 
Throughout this project, various machine learning concepts, data preprocessing techniques, and performance evaluation methodologies were explored and implemented.

## Problem Statement and Goals
The goal of this project is to develop an accurate and efficient predictive model that can forecast student test scores based on various academic and socio-economic factors. The project aims to:
- Identify key factors that impact student performance.
- Develop multiple machine learning models to predict scores accurately.
- Compare model performances and select the best approach.
- Provide visual insights for better understanding.
- Allow potential deployment for real-world use.

## Tech Stack
- **Programming Language**: Python
- **Libraries & Frameworks**:
  - Data Processing: pandas, numPy
  - Data Visualization: matplotlib, seaborn
  - Machine Learning: scikit-learn, XGBoost, LightGBM
  - Model Deployment: Flask
  - Environment & Development: Jupyter Notebook, VS Code
- **Frontend Development**: HTML, CSS

## Key Learnings and Topics Covered
This project introduced and reinforced several essential concepts in data science and machine learning, including:
- **Data Collection and Cleaning**: Understanding raw data, handling missing values, and ensuring data integrity.
- **Feature Engineering**: Selecting the most relevant features such as study hours, attendance, socio-economic background, and past performance to enhance prediction accuracy.
- **Exploratory Data Analysis (EDA)**: Using visualization techniques to identify trends, correlations, and potential biases in the data.
- **Machine Learning Model Selection and Implementation**:
  - Regression models (Linear, Polynomial)
  - Decision Trees and Random Forest
  - Support Vector Machines (SVM)
  - Neural Networks
  - Gradient Boosting Algorithms (XGBoost, LightGBM)
- **Hyperparameter Tuning**: Optimizing model performance using techniques such as grid search and cross-validation.
- **Performance Metrics**: Evaluating models based on RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R-squared scores.
- **Data Visualization**: Using Matplotlib and Seaborn to plot learning curves, feature importance, and predictive trends.

## Features
- **Comprehensive Data Preprocessing**: Handling missing values, normalizing numerical features, and encoding categorical variables.
- **Interactive EDA**: Generating insightful visualizations to understand student performance trends.
- **Multiple Machine Learning Models**: Implementing various regression and classification models for optimal performance.
- **Model Performance Comparison**: Evaluating different models to determine the most effective predictor.
- **Automated Report Generation**: Summarizing insights and model performance for easy interpretation.
- **Scalability**: Adapting the model for different datasets and education systems.

## Implementation
### 1. Data Preprocessing
- Data was sourced from educational datasets, cleaned, and transformed into a structured format.
- Numerical features were scaled using standardization techniques, while categorical features were one-hot encoded.
- Missing data was imputed using mean/mode imputation strategies.

### 2. Exploratory Data Analysis (EDA)
- Visualization techniques such as scatter plots, histograms, and correlation heatmaps were used to analyze relationships between features.
- Statistical summaries helped in identifying data distributions and outliers.

### 3. Model Training
- Various machine learning models were trained using Scikit-learn.
- Hyperparameter tuning was performed to optimize model performance.
- Feature importance analysis was conducted to understand the contribution of each factor in predicting test scores.

### 4. Model Evaluation
- Models were tested on unseen data, and their performance was compared using RMSE, MAE, and R-squared scores.
- Learning curves were plotted to identify overfitting or underfitting issues.

## Data
- The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data), containing student performance metrics and various influencing factors.

## Model Performance
- Multiple models were evaluated to determine the most effective predictor.
- The best model was selected based on its generalization capability and lowest error metrics

