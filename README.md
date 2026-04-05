# 📊 Telecom Customer Churn Prediction

## 📌 Project Overview
Customer churn is a critical problem in the telecom industry, where customers discontinue services. This project focuses on analyzing customer data and building machine learning models to predict churn.

The goal is to identify customers who are likely to leave and help businesses take proactive retention measures.

 

## 🎯 Objectives
- Perform data preprocessing and cleaning
- Handle missing values and outliers
- Train multiple machine learning models
- Evaluate models using performance metrics
- Compare models to find the best one

 

## 📂 Dataset
The dataset contains telecom customer information such as:
- Customer Age
- Gender
- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Payment Method
- Internet Service
- Tech Support
- Online Security
- Customer Support Calls

 

## 🛠️ Technologies Used
- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

 

## ⚙️ Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVC)
- Gradient Boosting
- XGBoost

 

## 📈 Model Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- AUC (ROC Score)

 

## 📊 Results Summary

| Model                | Accuracy | F1 Score | AUC   |
|---------------------|----------|----------|-------|
| Gradient Boosting   | 0.7708   | 0.5978   | 0.8305 |
| XGBoost             | 0.7601   | 0.5976   | 0.8236 |
| Random Forest       | 0.7630   | 0.5917   | 0.8175 |
| Decision Tree       | 0.7537   | 0.5951   | 0.6628 |
| Logistic Regression | 0.7488   | 0.5755   | 0.8082 |
| KNN                 | 0.7012   | 0.5243   | 0.7403 |
| SVC                 | 0.7544   | 0.4508   | 0.6959 |
 

## 🏆 Best Model
**Gradient Boosting** performed the best with:
- Highest Accuracy
- Highest F1 Score
- Highest AUC

 

## 🔍 Key Insights
- Ensemble models (Gradient Boosting, XGBoost, Random Forest) perform best
- Accuracy alone is not reliable due to class imbalance
- F1 Score and AUC give better evaluation
- SVC performed poorly due to low recall

 

## 📊 Visualization
- Model comparison graph using Accuracy & F1 Score
- Multi-line plots for performance comparison

 

## 🚀 Conclusion
Gradient Boosting is the most effective model for predicting customer churn in this dataset. Ensemble methods outperform traditional models due to their ability to capture complex patterns.

 

## 💡 Future Improvements
- Hyperparameter tuning
- Handling class imbalance (SMOTE)
- Deep Learning models (ANN)
- Feature engineering

 

## 👨‍💻 Author
**Rocky**

 

## ⭐ If you like this project
Give it a ⭐ on GitHub!
