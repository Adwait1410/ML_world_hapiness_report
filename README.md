# ML_world_hapiness_report
# 🌍 World Happiness Report - Data Cleaning & EDA

## 📌 Project Overview
This project focuses on **Data Cleaning, Exploratory Data Analysis (EDA), and Feature Selection** on the **World Happiness Report (2015)** dataset.  
It demonstrates how to handle missing values, outliers, categorical encoding, and correlation analysis before feature selection using different statistical methods.

---

## 📂 Project Structure

📁 World-Happiness-Report-ML/
├── world_happiness_report_ml.py # Main Python script
├── 2015.csv # World Happiness Report dataset (input)
└── README.md # Project documentation


---

## 🛠️ Technologies Used

| Tool/Library         | Purpose |
|----------------------|---------|
| Python               | Core language |
| Pandas, NumPy        | Data manipulation and numerical computations |
| Matplotlib, Seaborn  | Data visualization |
| Scikit-learn         | Feature selection, encoding, and imputation |
| SciPy                | Statistical operations |

---

## 🔹 Features Implemented

1. **Data Import and Exploration**
   - Load dataset using Pandas
   - Check shape, info, description, missing values, and duplicates

2. **Data Cleaning**
   - Missing value handling using `KNNImputer`
   - Outlier detection using IQR method and removal

3. **Categorical Encoding**
   - Label Encoding for `Region`
   - One-Hot Encoding for `Country`

4. **Visualization**
   - Histogram of Happiness Score  
   - Boxplots for key features  
   - Correlation heatmap  

5. **Feature Selection**
   - Variance Threshold method  
   - SelectKBest (F-regression & Chi-square)  
   - Mutual Information scores  


📊 Dataset
Source: World Happiness Report 2015

Contains indicators like Happiness Score, Region, Economy, Family, Health (Life Expectancy), and others.

📌 Sample Visualizations
Histogram of Happiness Score

Boxplot of Health vs Freedom

Correlation Heatmap of All Features

✨ Future Enhancements
Build machine learning models to predict Happiness Score

Automate data pipeline for new datasets




