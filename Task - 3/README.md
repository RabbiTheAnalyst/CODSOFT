# 💳 Credit Card Fraud Detection
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SMOTE](https://img.shields.io/badge/SMOTE-008000?style=for-the-badge&logo=smote&logoColor=white)

## 📌 Project Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), class imbalance handling, model training, hyperparameter tuning, and evaluation.

- **Algorithm**: Random Forest Classifier
- **Preprocessing**:
  - Handled missing values and outliers
  - Scaled features using StandardScaler
  - Addressed class imbalance with SMOTE
  - Train-test split for model validation
- **Hyperparameter Tuning**:
  - Used GridSearchCV for best parameter selection
- **Evaluation Metrics**:
  - **Accuracy Score**: 98.5%
  - **ROC-AUC Score**: 0.97
  - **Confusion Matrix & Classification Report**

## 📊 Exploratory Data Analysis (EDA)
The EDA phase provided key insights through visualizations:
- **Class Distribution**: Count plots showing imbalanced fraud vs. non-fraud transactions
- **Time vs. Transaction Amount**: Scatter plots to analyze spending patterns
- **Feature Scaling**: Standardized the 'Amount' feature and dropped 'Time'

## 🏆 Model Training & Results
- **Model**: Random Forest Classifier with optimized hyperparameters
- **Performance**:
  - **Accuracy**: 98.5% (indicating reliable fraud detection)
  - **ROC-AUC Score**: 0.97 (showing high discrimination capability)
  - **Confusion Matrix**: Heatmap visualization
  - **ROC Curve**: Plotted for model assessment

## 📁 Files
- [Jupyter Notebook with Full Code](https://github.com/RabbiTheAnalyst/CODSOFT/blob/main/Task%20-%203/Credit_Card_Fraud_Detection.ipynb)
- [Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)



