# Real Estate Price Prediction

## Overview

This project focuses on predicting real estate prices using machine learning regression techniques.

The project uses the Real Estate Valuation dataset and explores how property characteristics and geographical factors influence real estate prices.

The main objective is to build and evaluate regression models capable of estimating the price per unit area.

## Dataset

The dataset contains real estate transaction records with the following features:

- Transaction date
- House age
- Distance to the nearest MRT station
- Number of convenience stores nearby
- Geographic coordinates (latitude and longitude)

**Target variable:** House price of unit area.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Workflow

1. **Data Exploration:** Inspected the dataset and explored relationships between property features and prices.
2. **Data Preprocessing:** Prepared input features and handled missing values.
3. **Feature Transformation:** Applied feature scaling and preprocessing pipelines.
4. **Model Training:** Experimented with multiple regression algorithms.
5. **Hyperparameter Tuning:** Used GridSearchCV to explore model configurations.
6. **Model Evaluation:** Evaluated model performance using R² and Mean Squared Error (MSE).

## Models Explored

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Support Vector Regression
- K-Nearest Neighbors Regressor
- Other regression approaches

## Results

The Random Forest Regressor achieved the following results in the original notebook:

| Metric | Result |
|---|---:|
| R² Score | 0.807 |
| Mean Squared Error | 32.45 |

These results represent the experiment's reported evaluation and may vary depending on the data split and environment.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/gasolineee/Real-Estate-Price-Prediction-Machine-Learning.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn jupyter
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run the notebook cells sequentially.

## Learning Outcomes

- Practical experience with supervised machine learning.
- Understanding regression algorithms and model evaluation.
- Data preprocessing and feature scaling using Scikit-learn.
- Building machine learning pipelines.
- Hyperparameter optimization using GridSearchCV.

---

*An educational machine learning project focused on real estate price prediction.*
