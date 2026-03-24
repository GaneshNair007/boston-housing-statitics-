# 🏡 Boston Housing Data Analysis Project

## 📌 Overview

This project analyzes the **Boston Housing Dataset** to uncover key factors affecting housing prices. The goal is to provide **data-driven insights** that can help housing agencies and decision-makers understand pricing trends and make informed decisions.

---

## 🎯 Objectives

The analysis focuses on answering the following questions:

* Is there a significant difference in house prices based on proximity to the Charles River?
* How do housing prices vary with the age of properties?
* Is there a relationship between pollution levels and industrial areas?
* How does distance from employment centers impact housing prices?

---

## 🗂️ Dataset Information

The dataset contains various features related to housing in Boston, including:

* **MEDV**: Median value of owner-occupied homes (Target Variable)
* **CHAS**: Charles River dummy variable (1 = near river, 0 = not near)
* **AGE**: Proportion of owner-occupied units built before 1940
* **NOX**: Nitric oxide concentration (pollution level)
* **INDUS**: Proportion of non-retail business acres
* **DIS**: Weighted distance to employment centers
* **PTRATIO**: Pupil-teacher ratio

---

## 🛠️ Tools & Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Statsmodels

---

## 📊 Project Workflow

### 1. Data Exploration

* Checked data types, missing values, and duplicates
* Generated correlation matrix

### 2. Data Visualization

* Boxplots for price distribution
* Bar charts for categorical variables
* Scatter plots for relationships
* Histograms for distribution analysis

### 3. Statistical Analysis

* Levene’s Test (variance equality)
* T-test (price comparison based on river proximity)
* ANOVA (price variation across age groups)
* Pearson Correlation (pollution vs industrial areas)
* Linear Regression (impact of distance on price)

---

## 📈 Key Insights

* 🏞️ Houses near the Charles River show **differences in pricing**, indicating location-based value impact.
* 🏚️ Older properties tend to have **lower median values**, showing depreciation trends.
* 🏭 Higher industrial areas are associated with **increased pollution levels (NOX)**.
* 🚗 Distance from employment centers significantly **influences housing prices**.

---

## 📂 Project Structure

```bash
├── boston_housing.csv
├── analysis.ipynb
├── README.md
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/boston-housing-analysis.git
```

2. Navigate to the folder:

```bash
cd boston-housing-analysis
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run all cells to reproduce the analysis.

---

## 📤 Results

The project includes visualizations and statistical outputs that clearly explain the relationships between different housing factors and prices.

---

## 🧠 Conclusion

This analysis highlights how environmental, structural, and locational factors influence housing prices. These insights can support better urban planning and housing policy decisions.

---

## 🙌 Author

**Ganesh Nair**
AIML Student | Data Science Enthusiast

---

## ⭐ If you found this useful

Give this repo a star ⭐ and feel free to connect!
