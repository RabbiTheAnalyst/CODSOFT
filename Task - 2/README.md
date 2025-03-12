📊 Advertising Sales Prediction








📌 Project Overview
This project explores the relationship between advertising budgets (TV, Radio, Newspaper) and sales using the advertising.csv dataset. The goal is to predict sales based on advertising spend through data analysis and visualization. While the current notebook focuses on Exploratory Data Analysis (EDA), it lays the groundwork for a regression-based predictive model.

Objective: Predict sales using advertising expenditure
Dataset: advertising.csv (200 rows, 4 columns: TV, Radio, Newspaper, Sales)
Tools & Libraries:
Data manipulation with Pandas
Visualization with Matplotlib and Seaborn
Preprocessing:
Checked for missing values (none found)
Summary statistics for initial insights
📈 Exploratory Data Analysis (EDA)
The EDA phase provides a foundation for understanding the dataset:

Data Snapshot: Previewed the first 5 rows (df.head())
Structure: 200 entries, 4 columns (TV, Radio, Newspaper, Sales)
Missing Values: No null values (df.isnull().sum())
Summary Statistics: Descriptive stats (df.describe()) including mean, min, max, and quartiles
Visualization: Scatter plot setup for actual vs. predicted sales (incomplete due to missing y_test and predicted_y)
Future EDA Suggestions:

Correlation heatmap of features
Distribution plots (e.g., histograms, KDE) for TV, Radio, Newspaper, and Sales
🏆 Model Training & Results
Note: The notebook is incomplete and lacks model training.

Intended Model: Linear Regression (assumed based on scatter plot intent)
Visualization: Scatter plot of actual vs. predicted sales (requires model training)
Next Steps:
Split data into training and test sets
Train a Linear Regression model
Evaluate with metrics like R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)
Once completed, performance metrics and a finalized plot will be added.

📁 Files
Jupyter Notebook with Full Code
Advertising Dataset
