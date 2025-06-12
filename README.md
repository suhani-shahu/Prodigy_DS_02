# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs data cleaning and exploratory data analysis (EDA) on the Titanic dataset from [Kaggle's Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data) competition.

## 📌 Objective

The goal of this project is to explore and understand the dataset to identify key factors that influenced passenger survival. This includes:

- Handling missing data
- Analyzing survival rates across different features
- Visualizing patterns and correlations

---

## 📁 Dataset Used

- File: `train.csv`
- Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- Total entries: 891 passengers
- Features include: Name, Sex, Age, Pclass, Fare, Embarked, etc.

---

## 🔍 Key Explorations

- 👨‍👩‍👧‍👦 Survival distribution by **gender**
- 💼 Survival based on **passenger class**
- 📊 **Age distribution** and its role in survival
- 🌍 Port of **embarkation** and survival rate

---

## 🧼 Data Cleaning Steps

- Filled missing `Age` values with the **median**
- Filled missing `Embarked` values with the **mode**
- Dropped `Cabin` column due to excessive missing values

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook / Google Colab

---

## 📷 Sample Visualizations

- Survival Count Plot
- Survival by Sex / Pclass
- Age vs Survival (Boxplot)

---
