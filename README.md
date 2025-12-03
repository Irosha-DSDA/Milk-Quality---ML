# Milk-Quality---ML
Predicting milk quality using three machine learning techniques (Multinomial Logistic Regression, Random Forest, and XGBoost) in R

# 🥛 Modeling Milk Quality Using Machine Learning Techniques

Milk is considered an important factor in human life. High quality milk should not contain any toxins. Otherwise, it will be a high risk to human health. This study aims to predict milk quality using three different supervised machine learning
methods. 
- **Multinomial logistic regression model** is used as the baseline model
- **Random Forest**
- **XGBoost**

Evaluate the performance of selected three models using different statistical evaluation metrics such as,
- Accuracy
- Recall
- Precision
- F1 score

## Dataset

- Features: pH, Temperature, Taste, Odor, Fat, Turbidity, Color
- Target: Milk Grade (Low, Medium, High)
- Observations: 1,059  
- Source: Kaggle 

## Methods

Implemented in **R**
Continuous variables (pH, Temperature) are scaled and the target variable Grade is encoded (low-1, medium-2, high-3).
Train on 70% of data and evaluated on 30% test data.
Hyperparameter tuning was performed using **random search**.


<p align="center">
  <img src="Images/target.png" width="400" alt="Milk Quality Chart">
</p>

