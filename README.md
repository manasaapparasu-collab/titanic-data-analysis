# Titanic Survival Prediction 🚢

## 📌 Overview
This project analyzes the Titanic dataset to identify factors affecting passenger survival and builds machine learning models to predict survival.

## 🧹 Data Cleaning
- Removed Cabin column (many missing values)
- Filled missing Age with mean
- Filled missing Embarked with mode
- Dropped unnecessary columns

## 📊 Exploratory Data Analysis
- Survival rate by Gender, Class, and Embarkation
- Age distribution
- Correlation heatmap

## 🤖 Models Used
- Logistic Regression → 81%
- Decision Tree → 79%
- Random Forest → 82.6% (Best)

## 🔍 Key Insights
- Females had higher survival rate (~74%)
- First-class passengers had better survival chances
- Fare positively influenced survival
- Random Forest performed best

## 🛠 Tools & Technologies
- Python
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

## 📁 Files
- titanic_analysis.ipynb
- titanic.html
