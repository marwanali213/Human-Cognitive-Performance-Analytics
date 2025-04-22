# Human Cognitive Performance Analysis

## Overview


## Dataset
The dataset includes the following key features:
- Age
- Gender
- Sleep Duration
- Stress Level
- Diet Type
- Daily Screen Time
- Exercise Frequency
- Caffeine Intake
- Reaction Time
- Memory Test Score
- Cognitive Score

## Analysis Components

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Correlation analysis between variables
- Visualization of relationships using:
  - Histograms
  - Box plots
  - Violin plots
  - Correlation heatmaps
  - Pair plots

### 2. Feature Engineering
- Label encoding for categorical variables
- Feature importance analysis using Random Forest
- Data standardization

### 3. Machine Learning Models
The project implements and compares multiple regression models:
- Random Forest
- Extra Trees
- Gradient Boosting
- AdaBoost
- Linear Regression
- Ridge Regression
- Lasso Regression
- Passive Aggressive Regressor
- Support Vector Regression (SVR)
- Linear SVR
- K-Nearest Neighbors
- Decision Tree
- XGBoost
- Deep Neural Network (DNN)

## Key Findings
- Identified important factors influencing cognitive performance
- Analyzed stress level impact on cognitive scores
- Examined sleep duration effects on reaction time
- Compared performance of various machine learning models

## Requirements
```python
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
tensorflow
```

## Usage
1. Load the dataset
2. Run EDA cells to understand data distribution
3. Execute model training cells
4. Compare model performances

## Results
The notebook includes comprehensive model evaluation metrics:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared (R²)

## Contributing
Feel free to fork this project and submit pull requests for improvements.
