[← Back to Main Project README](../README.md)

# 🤖 Epic 4 – Model Building & Evaluation

In this phase, multiple machine learning algorithms are trained and evaluated to identify the most suitable model for predicting credit card approval.

---

## 📈 Logistic Regression
Logistic Regression serves as a baseline classification model.
![Logistic Regression Confusion Matrix](../figures/logistic_regression_confusion_matrix.png)

---

## 🌳 Random Forest
Random Forest is an ensemble learning algorithm.
![Random Forest Confusion Matrix](../figures/random_forest_confusion_matrix.png)

---

## 🚀 XGBoost
XGBoost is a gradient boosting algorithm that builds trees sequentially.
![XGBoost Confusion Matrix](../figures/xgboost_confusion_matrix.png)

---

## 🌲 Decision Tree
The Decision Tree model demonstrated the best overall performance.
![Decision Tree Confusion Matrix](../figures/decision_tree_confusion_matrix.png)

---

## ⚙️ Model Training Process
This chart illustrates the training phase of our selected models.
![Model Training Process](../figures/model%20training.png)

---
## 📊 Model Comparison
The performance of all three machine learning models is compared using evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC. 

**Model Comparison Chart:**
![Model Comparison Chart](../figures/model_comparsion.png)


---

## ✅ Conclusion
Based on the comparative analysis, the **Decision Tree** model was selected for deployment.
![Final Performance Summary](../figures/prediction.png)

The final model is hosted on [Render](https://credit-card-approval-prediction-oycw.onrender.com).
