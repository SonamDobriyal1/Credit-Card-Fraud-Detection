# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. It addresses the challenges of extreme class imbalance and evaluates models based on their ability to accurately identify rare fraud cases while minimizing false positives.

---

##  Objective

To develop a reliable machine learning system that can identify fraudulent transactions in credit card data by preprocessing, modeling, and evaluating using real-world data. The goal is to achieve high recall and precision on the fraud class while handling class imbalance effectively.

---

## Methodology

1. **Data Collection**  
   - Used a public credit card transaction dataset containing both fraudulent and legitimate records.

2. **Data Preprocessing**  
   - Handled missing values and scaled the `Amount` and `Time` features.
   - Performed exploratory data analysis and correlation heatmap.

3. **Feature Engineering**  
   - Analyzed feature importance and correlation with fraud.
   - Removed irrelevant or low-impact features if needed.

4. **Class Imbalance Handling**  
   - Applied **SMOTE** (Synthetic Minority Oversampling Technique) to balance the training data.

5. **Model Training**  
   - Trained multiple models including:
     - Random Forest Classifier
     - Logistic Regression

6. **Model Evaluation**  
   - Evaluated models using:
     - Accuracy
     - Precision, Recall, F1-score
     - Confusion Matrix
     - ROC and Precision-Recall Curves

---

## Results Summary

- **Accuracy**: 99.94%
- **Recall (Fraud Class)**: 83%
- **Precision (Fraud Class)**: 83%
- Very low false positive and false negative rates, showing balanced performance.

---

## Visualizations

- Correlation heatmap of features
- Feature importance plot
- ROC and Precision-Recall curves
- Confusion matrix visualization

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---
