# 📊 McDonald's Financial Trend Analysis (2021–2024) & Predictive Modeling

Welcome to this professional data science notebook focused on analyzing and modeling financial data from **McDonald's**. This project is developed by **Waqar Ali** as part of a hands-on portfolio to showcase real-world data analysis, visualization, and machine learning practices.

---

## 📁 Dataset Overview:

The dataset contains financial data extracted from various reports and sources for the years **2021, 2022, 2023, and 2024**. Key features include:

- `table`: Category/type of financial entry (e.g., Revenue, Cost, Expenses)
- `heading`: Main classification (e.g., Income Statement)
- `subheading`: Specific detail or financial metric
- `2021–2024`: Year-wise numeric financial data

Unnecessary unnamed columns were dropped during preprocessing.

---

## 🎯 Project Objectives:

- 🧹 Clean and prepare the data for analysis and machine learning
- 📈 Perform exploratory data analysis (EDA) to uncover financial patterns
- 📊 Visualize trends using consistent and aesthetically pleasing color schemes (orange & blue)
- 🤖 Apply machine learning regression models to predict future financial trends
- 📋 Interpret model results and performance
- 📦 Package the project for public sharing and open-source contribution

---

## 🛠️ Technologies & Libraries Used

- **Python 3**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – static and advanced visualizations
- **Plotly** – interactive graphs
- **Scikit-learn** – machine learning models and preprocessing
- **Warnings, OS, and Others** – clean output and manage environment

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for null/missing values
- Cleaned financial data entries (removed commas, converted types)
- Identified top trends across years
- Visualized trends with:
  - Bar plots
  - Line plots
  - Heatmaps
  - Interactive visuals using Plotly

All visuals followed a consistent **orange and blue theme** to ensure clarity and visual harmony.

---

## 🤖 Machine Learning: Predictive Modeling

After EDA, machine learning models were trained to predict future values of selected financial metrics.

- **Model Used:** Linear Regression (Scikit-learn)
- **Features:** Table Type, Year, and other categorical/numeric features
- **Target:** Future financial figures
- **Workflow:**
  - Label Encoding of categorical data
  - Train-Test Split
  - Model Training
  - Model Evaluation using R² Score and MAE
  - Result Interpretation

---

## 📌 Key Insights

- McDonald's showed consistent growth in specific financial metrics from 2021 to 2024
- Some cost centers increased sharply in 2023–2024
- Regression models accurately predicted trends with good performance metrics
- The visual representation helped clearly distinguish patterns over time

---

## Dataset Link

https://www.kaggle.com/datasets/harishthakur995/mcdonalds-finanacial-data-2021-2024

---


## License 📜

This project is licensed under the MIT License - see the LICENSE file for details.

---


## Uploaded Date 📅

July 19, 2025

---


## Author ✍️

Waqar Ali

---
