# Task 2: Exploratory Data Analysis (EDA)

This repository contains my work for **Task 2 of the Elevate Labs Internship**. The objective of this task was to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the data, identify patterns, and make visual inferences.

---

## 📌 Objective

- Understand the Titanic dataset through visual and statistical analysis
- Generate descriptive statistics (mean, median, standard deviation, etc.)
- Create histograms, boxplots, and heatmaps to explore data distribution
- Analyze feature relationships and correlations
- Draw basic inferences from visualizations

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

## 🧪 Dataset Used

- **Name:** Titanic-Dataset.csv  
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🔍 Steps Performed

### 1. **Loading & Overview**
- Loaded the dataset using pandas and displayed the first few rows.
- Checked column data types, null values, and general structure using `.info()` and `.describe()`.

### 2. **Descriptive Statistics**
- Generated statistical summaries for numerical and categorical features.
- Identified missing values and distributions of features.

### 3. **Visualizations**
- **Histograms** to show distributions of numerical features like `Age` and `Fare`.
- **Boxplots** to detect outliers and distribution across categories (e.g., `Age` vs `Pclass`).
- **Pairplot** to visualize relationships between features like `Age`, `Fare`, and `Survived`.
- **Heatmap** to understand correlation between numeric features.

### 4. **Feature-Level Analysis**
- Analyzed survival rates across **gender** and **passenger class** using countplots.
- Observed trends in **Age** and **Fare** distributions.
- Inferred that **females and first-class passengers** had higher survival rates.

---

## 📸 Sample Visuals

- Pairplot: Survival trends across age and fare
- Heatmap: Correlation matrix
- Countplot: Survival by gender and class
- Histogram: Age distribution

---

## ✅ Final Inference

- Gender and passenger class significantly influence survival.
- Higher fare-paying passengers tended to survive more.
- Data is suitable for building predictive ML models with selected features.

