# 🔍 Titanic Dataset – Exploratory Data Analysis (EDA)

## 🚀 Overview

This project performs a complete Exploratory Data Analysis (EDA) on the Titanic Dataset using Python, Pandas, Matplotlib, and Seaborn. The goal is to understand the dataset, clean missing values, explore patterns, and identify key factors that influenced passenger survival.

## 📂 Dataset

Dataset Name: Titanic Dataset

Rows: ~500

Columns: 12

Features: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

## 🧹 Data Cleaning

Checked dataset structure and summary using .info() and .describe()

Identified missing values using heatmap and percentage analysis

Age: Filled with median and converted to integer

Fare: Filled with median

Cabin: Dropped due to 70%+ missing

Ensured consistent datatypes and categories

## 📊 Exploratory Analysis

Histplots for numerical distributions

Boxplots for outliers (Age & Fare)

Countplots for categorical variables

Pairplots for multivariate relationships

Correlation heatmap to visualize variable relationships

## 🔎 Key Insights

Females and first-class passengers had the highest survival rates

Fare strongly correlates with Pclass

Age distribution shows fewer older passengers

Several extreme outliers found in Fare

Embarked location influences survival

## 🛠️ Tech Stack

Python

Pandas

Matplotlib

Seaborn

## 📁 Project Contents

Jupyter Notebook (EDA steps)

Plots & visualizations

Final report 

✔️ Conclusion

This EDA provides a clear understanding of the Titanic dataset, revealing important survival patterns and preparing the data for further modeling or predictive analysis.
