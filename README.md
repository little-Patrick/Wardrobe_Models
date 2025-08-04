# Retail Customer Churn Prediction

This project focuses on predicting customer churn for a retail e-commerce business using machine learning. The goal is to identify customers at risk of leaving the platform and understand the factors driving churn. These insights enable the business to implement targeted retention strategies, improve customer satisfaction, and reduce churn rates.

## Key Features
- **Churn Prediction**: Predict whether a customer is likely to churn.
- **Feature Insights**: Identify key factors influencing churn.
- **Model Evaluation**: Compare multiple machine learning models and optimize the best one.

## Dataset
The dataset (`ecommerce_customer_data.csv`) contains 15,000 customer records with 14 features and a target variable (`churn`). Key features include:
- Account age, average orders, order value, returns rate, satisfaction score, and more.

## Technical Process
1. **Data Preparation**: Load and preprocess the dataset, split into training and testing sets.
2. **Exploratory Data Analysis (EDA)**: Analyze class distribution and feature correlations.
3. **Model Training**:
   - Baseline Random Forest model.
   - Boosting models: AdaBoost, Gradient Boosting, and XGBoost.
4. **Hyperparameter Tuning**: Optimize the best model (XGBoost) using GridSearchCV.
5. **Final Evaluation**: Evaluate the model using accuracy, classification report, and feature importance.

## Results
- The final model achieves high accuracy and provides insights into the most important features driving churn.

## Usage
1. Run the Jupyter Notebook to train and evaluate the model.
2. Export the trained model to predict churn for new customer data.

## Requirements
- Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

## Future Work
- Deploy the model as a web API for real-time predictions.
- Explore additional metrics like recall or F1-score for optimization.