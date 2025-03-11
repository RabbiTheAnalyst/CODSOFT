# 🚢 Titanic Survival Prediction (Task 1)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?&style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)

## 📌 Project Overview
This project, completed as Task 1 of the CodSoft Data Science Internship (Feb 2025), predicts passenger survival on the Titanic using machine learning. The workflow includes data preprocessing, exploratory data analysis (EDA), and modeling with Logistic Regression, achieving an AUC score of 0.88.

## 🛠️ Tools & Technologies
- **Programming Language**: Python 🐍
- **Libraries**:
  - `pandas` - Data manipulation and analysis
  - `matplotlib` - Visualization of data trends
  - `seaborn` - Enhanced statistical graphics
  - `scikit-learn` - Machine learning implementation and evaluation
- **Algorithm**: Logistic Regression
- **Preprocessing**:
  - `StandardScaler` for feature scaling
  - `LabelEncoder` for categorical variables
  - Train-test split for model validation
- **Evaluation Metrics**:
  - Accuracy Score
  - Classification Report (Precision, Recall, F1-Score)
  - ROC-AUC Score

## 📊 Exploratory Data Analysis (EDA)
The EDA phase provided key insights through visualizations:
- **Survival Counts**: Bar chart of survivors vs. non-survivors
- **Gender-Based Survival**: Count plots by gender
- **Passenger Class (Pclass)**: Survival rates across classes
- **Family Size (SibSp) & Embarkation**: Impact on survival
- **Age & Fare Distribution**: KDE plots for data spread
- **Correlation Heatmap**: Feature interrelationships

## 🏆 Model Training & Results
- **Model**: Logistic Regression with standardized features
- **Performance**:
  - **Accuracy**: ~0.82
  - **ROC-AUC**: 0.88
  - Detailed classification report (precision, recall, F1-score)
- **ROC Curve**: Visualized to demonstrate model robustness

### 📈 Key Visualization
![ROC Curve]("H:\CodSoft\Task -  01\ROC-Curve.png")  
*AUC of 0.88 reflects strong predictive capability.*

## 📁 Files
- `Titanic_Prediction.ipynb`: Jupyter notebook with full code
- `Titanic-Dataset.csv`: Dataset used for analysis

