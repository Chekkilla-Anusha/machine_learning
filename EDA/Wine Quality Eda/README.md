# 🍷 Wine Quality – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Wine Quality (WineQT)** dataset to understand how different chemical properties of wine influence its quality rating. The analysis focuses on data cleaning, feature engineering, statistical analysis, and insightful visualizations.

The goal is to extract meaningful patterns that can later support **machine learning models** or **business insights** in the wine industry.

---

## 📂 Dataset Information

* **Dataset Name:** WineQT (Wine Quality)
* **Format:** CSV
* **Target Variable:** `quality`
* **Type:** Structured, numerical dataset

### Key Features

* fixed acidity
* volatile acidity
* citric acid
* residual sugar
* chlorides
* free sulfur dioxide
* total sulfur dioxide
* density
* pH
* sulphates
* alcohol
* quality (output label)

---

## 🧹 Data Preprocessing

* Checked dataset shape, structure, and data types
* Removed unnecessary columns (e.g., `S.No.` if present)
* Checked for missing values and duplicates
* Converted data types where required
* Performed statistical summary using `describe()`

---

## 🛠 Feature Engineering

New categorical features were created for better interpretability:

* **Sugar Level** (from `residual sugar`)

  * Low, Medium, High
* **Acidity Level** (from `pH`)

  * High, Medium, Low
* **Alcohol Strength** (from `alcohol`)

  * Low, Medium, High, Very High

Category labels were simplified for cleaner analysis.

---

## 📊 Exploratory Data Analysis

### Univariate Analysis

* Distribution of wine quality scores
* Histograms with skewness for numerical features

### Bivariate Analysis

* Alcohol vs Quality (Swarm Plot)
* Alcohol vs Quality (Violin Plot)
* Box Plot analysis
* Pair Plot to study feature relationships

### Statistical Analysis

* Mean, median, variance
* Skewness of numerical variables

---

## 📈 Key Insights

* Alcohol content has a **strong positive relationship** with wine quality
* Most wines fall into **medium quality categories (5–6)**
* Certain chemical properties show skewed distributions
* Higher alcohol strength wines tend to receive higher quality ratings

---

## 🧰 Technologies Used

* **Python**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **Jupyter Notebook** – Interactive analysis

---

## 🚀 Future Enhancements

* Apply machine learning models for quality prediction
* Feature importance analysis
* Model evaluation and comparison
* Deploy insights using dashboards

---

