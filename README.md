# Personalized Nutrition System: A Machine Learning Approach to Tailored Diets 
This repository contains the **machine learning part** of a Personalized Nutrition System. 
The model predicts an individual's **diet type** based on dietary habits and lifestyle factors. 
This part of the project focuses **only on the ML pipeline** — the data science preprocessing and cleaning are handled separately.

This part of the project focuses **only on the ML pipeline**  the data science preprocessing and cleaning are handled separately.

---

## Features
- **Diet-Type Prediction**: Classifies users into diet categories (e.g., vegetarian, vegan, omnivorous) based on lifestyle and dietary patterns.
- **Data Preprocessing**:
  - Encoding categorical variables
  - Scaling numerical features
  - Handling class imbalance using **SMOTE**
- **Modeling & Evaluation**:
  - Implemented **XGBoost** and **Random Forest**
  - Applied **cross-validation** for reliable performance estimates
  - Used **GridSearchCV** and **RandomizedSearchCV** for hyperparameter tuning
- **Performance Metrics**: Accuracy, F1-score, balanced accuracy, ROC-AUC

---

## Technologies Used
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Imbalanced-learn, XGBoost
- **Visualization**: Matplotlib, Seaborn
- **Models Used**: XGBoost, Random Forest  
- **Model Optimization & Evaluation**: StratifiedKFold, GridSearchCV, RandomizedSearchCV