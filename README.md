# 💳 Credit Card Fraud Detection Model

***

## 📝 Project Description

This repository presents a **Credit Card Fraud Detection Model** designed to accurately classify financial transactions as either **legitimate** or **fraudulent**.

The project tackles the challenge of **highly imbalanced datasets** typical of fraud detection, where fraudulent transactions are extremely rare. Key steps involve:

* **Data Prepration** generation of the flat file from raw data sources (Kaggle)
* **Exploratory Data Analysis (EDA):** Investigating the distribution of features and the nature of the transaction data.
* **Data Preprocessing:** Data Encoding, Scaling and evalaution of the diffrent balancing methods. 
* **Model Training & Evaluation:** Implementing and comparing various machine learning classifiers (such as Logistic Regression, Random Forest, or Gradient Boosting) optimized to maximize **Recall** (the ability to correctly identify actual fraud cases) while maintaining acceptable **Precision**.

The final result is a robust classification model capable of providing valuable insight into potentially malicious financial activity.

***

## ⚙️ Technical Stack

This project is built primarily using **Python** and relies on the following core libraries:

* **Pandas & NumPy:** Data manipulation.
* **Scikit-learn:** Model implementation and evaluation.
* **Imbalanced-learn (imblearn):** Handling class imbalance.
* **Matplotlib & Seaborn:** Data visualization.

***

## 🚀 Installation and Setup

Follow these steps to set up the project locally:

### 1. Clone the repository

```bash
git clone [https://github.com/Shogant/Credit_Card_Fraud_Detection_Model.git](https://github.com/Shogant/Credit_Card_Fraud_Detection_Model.git)
cd Credit_Card_Fraud_Detection_Model
## Dataset
Download the dataset from [Kaggle](https://www.kaggle.com/datasets/karthikgangula/credit-card-fraud-mega-dataset)  
Place the CSV files inside the `data/` folder before running notebooks.
