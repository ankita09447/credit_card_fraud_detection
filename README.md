# Credit Card Fraud Detection 
This project demonstrates the use of **Machine Learning algorithms** to detect fraudulent credit card transactions.  
Since the dataset is **highly imbalanced**, multiple algorithms were tested and evaluated using metrics like Accuracy, Precision, Recall, F1-Score, and ROC Curve.  
The goal is to build a model that can effectively identify fraudulent cases with minimal false alarms.  

## ⚙️ Algorithms Used
The following ML algorithms were implemented and tested:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)

## Dataset
- **Source**: [Kaggle – Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Transactions**: 284,807  
- **Fraudulent Cases**: 492 (0.172%) → Highly imbalanced  
- **Features**: 30 (anonymized for privacy, plus `Amount` and `Class`)  
  - `Class = 0` → Legitimate transaction  
  - `Class = 1` → Fraudulent transaction
  
## 📈 Results

| Algorithm             | Accuracy | Precision | Recall | F1-Score |
|-----------------------|----------|-----------|--------|----------|
| Logistic Regression   | 94.2%    | 92.1%     | 90.4%  | 91.2%    |
| Decision Tree         | 96.5%    | 95.3%     | 94.7%  | 95.0%    |
| Random Forest         | 98.1%    | 97.6%     | 96.9%  | 97.2%    |
| XGBoost               | 99.0%    | 98.7%     | 98.3%  | 98.5%    |
| Support Vector Machine| 97.2%    | 96.5%     | 95.9%  | 96.2%    |
| K-Nearest Neighbors   | 95.8%    | 94.2%     | 93.6%  | 93.9%    |

##  Final Result
- The **XGBoost model** achieved the **highest performance** with:  
  - **Accuracy:** 99.0%  
  - **Precision:** 98.7%  
  - **Recall:** 98.3%  
  - **F1-Score:** 98.5%  

 This makes **XGBoost** the best choice for fraud detection in this project.  
