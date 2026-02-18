# 📊 Exploratory Data Analysis on Indian Mutual Funds

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DhruvPatel190/EDA-Project/blob/main/EDA_Final_Project.ipynb)

## 📌 Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on Indian Mutual Funds, with a special focus on Liquid Mutual Funds and NAV time-series analysis.

The objective is to uncover patterns in fund performance, risk distribution, asset allocation, and long-term growth trends across multiple Asset Management Companies (AMCs).

The project is structured into three major datasets:

1. **Liquid Mutual Funds Analysis**
2. **Overall Mutual Fund Market Analysis**
3. **NAV Time Series Analysis of Fund Houses**

This structured EDA approach ensures meaningful financial insights for better investment understanding and decision-making.

---

## 🗂️ Dataset Breakdown

### 🔹 Dataset 1 – Liquid Mutual Funds (India)

**Objective:**  
Analyze risk profile, ratings, and return behavior of Liquid Mutual Funds.

**Key Analysis Performed:**
- Filtered Liquid Funds from overall dataset
- Removed duplicates and irrelevant features
- Analyzed risk vs 1-year return
- Studied AMC-wise performance
- Evaluated rating distribution

**Key Insights:**
- Moderate-risk funds tend to provide better returns.
- Most liquid funds fall under average (3-star) ratings.
- Performance varies significantly even within the same category.
- Certain AMCs consistently outperform others.

---

### 🔹 Dataset 2 – Overall Mutual Fund Market

**Objective:**  
Understand broader mutual fund performance across categories.

**Key Analysis Performed:**
- Missing value and outlier detection
- Statistical summaries
- AMC-wise AUM comparison
- Growth vs IDCW distribution
- Risk vs performance evaluation

**Key Insights:**
- A small number of AMCs manage the majority of total AUM.
- Investors prefer Growth options over IDCW.
- Returns and volatility vary significantly across fund categories.
- Diversification and fund type strongly impact performance.

---

### 🔹 Dataset 3 – NAV Time Series Analysis

**Objective:**  
Compare long-term performance of different mutual fund houses using NAV data.

**Key Analysis Performed:**
- Loaded multiple Excel NAV datasets
- Cleaned and formatted date columns
- Combined NAV data across fund houses
- Normalized and visualized time-series trends

**Key Insights:**
- Most funds show long-term upward growth trends.
- Some funds exhibit smoother NAV growth (lower volatility).
- Others show steeper curves, indicating higher risk-return potential.
- Clear visual differentiation between outperforming and underperforming funds.

---

## 📊 Techniques Used

- Data Cleaning & Preprocessing  
- Missing Value Handling  
- Outlier Detection  
- Statistical Summary Analysis  
- Correlation Analysis  
- Bar Charts, Pie Charts, Scatter Plots  
- Time Series Visualization  
- NAV Normalization  

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel Data Handling

---

## 📈 Business & Financial Value

This analysis helps:

- Understand risk-return trade-offs
- Evaluate AMC performance
- Identify stable vs volatile funds
- Compare long-term wealth creation potential
- Support informed investment decisions

---

## 🚀 How to Run This Project

1. Clone this repository  
2. Open `EDA_Final_Project.ipynb` in:
   - Jupyter Notebook OR  
   - Google Colab  
3. Run all cells sequentially  

---

