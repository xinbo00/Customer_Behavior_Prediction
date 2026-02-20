# Customer Behavior Prediction

## Project Overview
This project explores whether basic customer demographic and purchase features can predict:

- Discount usage  
- Subscription likelihood  

Using logistic regression and KNN models, the analysis evaluates the predictive signal contained in simple customer attributes and discusses implications for marketing targeting.

---

## Business Problem
Marketing teams often need to identify customers who are more likely to respond to promotions or subscribe to services.  
This project builds baseline machine learning models to assess the predictive power of available customer features.

---

## Methods Used
- Logistic Regression
- K-Nearest Neighbors
- Stratified train-test split
- ROC-AUC evaluation
- Confusion matrix and classification report

---

## Key Results
- Discount prediction AUC ≈ 0.50  
- Subscription prediction AUC ≈ 0.56  
- Models show limited predictive power using only demographic and purchase summary features.

---

## Business Insights
- Current features provide weak predictive signal, suggesting customer behavior is not strongly driven by demographics alone.
- Models tend to favor the majority class under default thresholds, indicating threshold tuning may be required in real marketing applications.
- Incorporating richer behavioral data (e.g., engagement history, promotion exposure) would likely improve targeting performance.

---

## Tools & Technologies
- Python (pandas, scikit-learn, matplotlib)
- Jupyter Notebook

---

## Next steps
- Add behavioral and engagement features
- Perform feature engineering
- Explore more advanced models
- Evalute business-specific decision thresholds
