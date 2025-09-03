# Wardrobe Models

Welcome to the **Wardrobe Models** repository! This project serves as a model creation and evaluation "playground" for a PySide-based Qt application. The application is designed for customer data exploration, allowing users to run customer data through various machine learning models created and tested in this repository.

## Repository Structure

The repository is organized into the following directories:

### 1. `customer_churn`
- **Purpose**: Contains models and data for predicting customer churn.
- **Contents**:
  - `ecommerce_customer_data.csv`: Dataset for e-commerce customer churn analysis.
  - `retail_churn_ensemble_lab.ipynb`: Jupyter notebook for building and evaluating ensemble models for churn prediction.

### 2. `loan_risk`
- **Purpose**: Focuses on assessing financial loan risks.
- **Contents**:
  - `financial_loan_data.csv`: Dataset for financial loan risk analysis.
  - `Loan.csv`: Additional loan-related data.
  - `financial_loan_risk.ipynb`: Jupyter notebook for creating and evaluating loan risk models.
  - `moneyIMG.webp`: Supporting image for visualization.

### 3. `return`
- **Purpose**: Analyzes product return data to predict return likelihood.
- **Contents**:
  - `product_return_data.csv`: Dataset for product return analysis.
  - `retail_return_model_lab.ipynb`: Jupyter notebook for building and testing return prediction models.

## Features

- **Data Exploration**: Each notebook includes data preprocessing, visualization, and exploration steps.
- **Model Development**: Build and evaluate machine learning models tailored to specific business problems.
- **Integration**: Models are designed to integrate seamlessly with the PySide Qt application for real-time data analysis.

### Using the Models in the PySide Application
1. Export the trained models from the notebooks.
2. Integrate the models into the PySide Qt application for customer data exploration.

