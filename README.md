# Customer Churn Prediction in E-Commerce  

## Overview  
This project predicts **customer churn** in an e-commerce platform using **Machine Learning models**. The goal is to help businesses identify potential churners and take proactive steps to retain customers.  

##  Features  
- **Data Preprocessing:** Handling missing values, encoding categorical variables, scaling numerical features.  
- **Machine Learning Models:** Logistic Regression, Random Forest, Gradient Boosting, Decision Trees.  
- **Feature Engineering:** Used SMOTE to address class imbalance and PCA for dimensionality reduction.  
- **Model Evaluation:** Performance measured using Accuracy, Precision, Recall, and F1-score.  
- **Customer Segmentation:** Applied K-Means clustering to group customers based on behavior.  
- **Data Visualization:** Used Matplotlib & Seaborn for insights.  

##  Tech Stack  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning Models:** Logistic Regression, Decision Trees, Random Forest, Gradient Boosting  
- **Data Processing:** Feature Engineering, SMOTE, PCA  

##  Dataset  
The dataset contains customer transaction history, demographics, and engagement metrics.  
- **Features Include:** Customer ID, Purchase Frequency, Last Purchase Date, Total Spend, etc.  
- **Target Variable:** Churn (1 = Customer Churned, 0 = Retained)  

##  Model Performance  
| Model | Accuracy | Precision | Recall | F1-Score |  
|--------|----------|------------|---------|------------|  
| Logistic Regression | 75.2% | 72.8% | 70.5% | 71.6% |  
| Random Forest | **79.3%** | **78.4%** | **77.1%** | **77.7%** |  
| Gradient Boosting | 78.1% | 76.9% | 75.4% | 76.1% |  

 **Random Forest performed the best with an accuracy of 79.3%.**  

##  How to Run  
 **Clone the repository**  
```bash
git clone https://github.com/Mohammedkaif07/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
