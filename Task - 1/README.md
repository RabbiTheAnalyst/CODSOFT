# 🚢 Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-%23FF6F00.svg?&style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)

## 📌 Project Overview
This project predicts survival on the Titanic using machine learning techniques. The dataset undergoes preprocessing, exploratory data analysis (EDA), and modeling with Logistic Regression.

## 🛠️ Technologies Used
- **Programming Language:** Python 🐍
- **Libraries:**
  - `pandas` - Data manipulation
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical graphics
  - `scikit-learn` - Machine learning models & evaluation
- **Machine Learning Algorithm:**
  - Logistic Regression
- **Data Processing:**
  - StandardScaler (Feature Scaling)
  - Label Encoding (Categorical Data)
  - Train-Test Split
- **Model Evaluation Metrics:**
  - Accuracy Score
  - Classification Report
  - ROC-AUC Curve

## 📊 Exploratory Data Analysis (EDA)
Key visualizations included:
- **Survival Counts:** Bar charts showing survivors vs. non-survivors.
- **Gender-Based Survival:** Count plots analyzing male vs. female survival rates.
- **Pclass Impact on Survival:** Visualization of class-based survival rates.
- **SibSp & Embarked Analysis:** Insights on survival based on family size and embarkation point.
- **Age & Fare Distribution:** Kernel Density Estimations (KDE) for better data distribution understanding.
- **Correlation Heatmap:** Identifying feature relationships.

## 🏆 Model Training & Evaluation
- **Logistic Regression Model** trained with standardized features.
- Predictions assessed with:
  - **Accuracy Score** for performance measurement.
  - **Classification Report** (Precision, Recall, F1-score).
  - **ROC-AUC Curve** showcasing model effectiveness.

### 🔍 ROC Curve Analysis
A high **AUC score of 0.88** indicates a well-performing model with an effective balance between True Positives and False Positives.

## 📷 Visual Results
![Survival Count](assets/survival_count.png)
![ROC Curve](assets/roc_curve.png)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/titanic-survival.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python titanic_model.py
   ```

---
📌 *This project demonstrates the power of data preprocessing, exploratory analysis, and predictive modeling in solving real-world classification problems!*


