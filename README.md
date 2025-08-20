This project is a solution for the **[Binary Classification with a Bank Dataset](https://www.kaggle.com/competitions/playground-series-s5e8/overview)** competition on Kaggle's Playground Series. The main objective is to predict whether a client will subscribe to a bank term deposit based on a variety of personal and marketing campaign data.

---
## Model: 
Several popular machine learning algorithms were explored to find the best fit for this binary classification problem:
    * **Logistic Regression**: Used as a baseline to establish initial performance.
    * **Random Forest**: An ensemble method that helps to reduce overfitting and improve predictive power.
    * **XGBoost & LightGBM**: These powerful gradient boosting frameworks were used to achieve high performance due to their efficiency and accuracy.

---
## Evaluation
Submissions are evaluated using ROC AUC between the predicted value and the observed target.
The final model (LightGBM), a combination of the above approaches, achieved a score of **0.96887**.

