# Housing-Price-Prediction-and-Model-Optimization

This project focuses on predicting housing prices in California using various regression models. The models are optimized using Optuna, a hyperparameter optimization framework. The project involves feature engineering, model training, and evaluation of multiple regression models.

## Project Overview

- **Objective:** Predict housing prices in California and optimize model performance.
- **Dataset:** Housing data for various regions in California.
- **Models Used:**
  - SGD
  - LinearSV
  - KNeighbors
  - DecisionTree
  - Tree Ensembles
      - ExtraTrees 
      - RandomForest
  - Boosting Ensembles
      - AdaBoost
      - GradientBoosting
      - XGBoost
- **Optimization Tool:** Optuna
- **Evaluation Metric:** Root Mean Squared Error (RMSE)
- **Frameworks and Libraries:** Python, scikit-learn, XGBoost, Optuna, Matplotlib

## Project Structure

- `housing_prices.ipynb`: Jupyter Notebook containing the full project code.
- `README.md`: Project documentation.

## Feature Engineering

- Created new features to enhance model performance.
- Normalized and scaled features for better model training.

## Model Optimization

- Used Optuna to tune hyperparameters for each regression model.
- Evaluated models using cross-validation and selected the best performing hyperparameters.

## Results

- Visualized the RMSE of each model.
- Compared the performance of different models.
- Plotted the tuning time for each model to analyze efficiency.


## Conclusion

This project demonstrates the process of predicting housing prices using various regression models and optimizing them for better performance. The use of feature engineering and hyperparameter optimization significantly improves model accuracy.
