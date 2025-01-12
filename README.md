# Assigning Field Positions to Football Players

## Overview
This project predicts the best field positions for soccer players based on their attributes from the FIFA dataset. The goal is to assist team managers in optimizing player placement for better performance. 

## Dataset
- **Source:** FIFA-23 complete player dataset.
- **Features Used:** 52 player attributes, grouped and preprocessed to reduce redundancy.
- **Class Labels:** 10 positions, e.g., LF, CM, GK.

## Methodology
1. **Data Preprocessing:** Feature selection, scaling, encoding, and handling class imbalance using CTGAN.
2. **Models Implemented:**
   - Multiclass Logistic Regression
   - Random Forest
   - Decision Tree
   - Gaussian Naive Bayes
   - SVM
   - MLP
   - Boosting Algorithms (Adaboost, Gradient Boost, XGBoost)
   - KNN
3. **Evaluation:** Accuracy, Precision, Recall, F1-Score, and 5-Fold Cross Validation.

## Results
- **Best Model:** Support Vector Machine (SVM) with an accuracy of 73.2%.
- **Comparison:** Multiclass Logistic Regression, Random Forest, and MLP also performed well.

## Insights
- Direct 10-class classification outperformed separate horizontal and vertical position models.
- Ensemble techniques like boosting improved model performance.

## Future Prospects
Deploying the models to aid managers and analysts in making data-driven decisions in soccer.

**Team Members:**  
- Ishita (2022224)  
- Jessica Kaur Chawla (2022230)  
- Kartikeya (2022242)  
- Medha (2022292)  
