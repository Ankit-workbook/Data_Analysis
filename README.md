

# 📊 Financial Investment Behavior Analysis

This project explores investor behavior using survey data collected in `Finance_data.csv`. The goal is to uncover insights into investment preferences, objectives, return expectations, and behavioral patterns across different demographics.

---

## 📁 Dataset Overview

- **Rows:** 40
- **Columns:** 24
- **Data Type:** Survey responses (categorical, ordinal, and numeric)
- **Focus Areas:** Gender, Age, Investment Avenues, Return Expectations, Preferences, and Objectives

---

## 🔍 Key Questions

- Who invests in the stock market and why?
- What are the most preferred investment avenues?
- How do investment goals vary by gender or age?
- What return expectations do investors have?
- What correlations exist between preferences?

---

## 🧼 Data Cleaning

Performed the following cleaning steps using `pandas`:
- Standardized column names and values (`str.strip().title()`)
- Checked for missing/null values (none found)
- Fixed inconsistent labels (e.g., `Stock_Marktet` ➝ `Stock_Market`)
- Converted rankings to numeric for preference comparison

---

## 📊 Key Insights

| Category                       | Insight                                                                 |
|--------------------------------|-------------------------------------------------------------------------|
| **Gender**                    | 62.5% Male, 37.5% Female investors                                      |
| **Stock Market Participation** | 87.5% of respondents invest in stocks                                  |
| **Investment Objectives**      | 65% aim for capital appreciation                                       |
| **Return Expectation**         | Majority expect 20–30% returns                                         |
| **Preferred Avenues**          | Mutual Funds and Equity Market top the list                            |
| **Age Group**                  | Young investor base (avg age ~28)                                      |
| **Preference Correlation**     | Mutual Funds & Equity positively correlated; Bonds & PPF cluster too   |

---

## 📈 Analysis Performed (No Graphs Used)

- Value counts using `df['column'].value_counts()`
- Grouped analysis using `df.groupby()`
- Crosstabs for comparing features like:
  - `Objective` vs `Avenue`
  - `Gender` vs `Objective`
- Correlation matrix using `df.corr()`
- Ranking preference analysis using `.mean().T.sort_values()`

---

## 💻 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- numpy
- seaborn
- sql
- tableau
- matplotlib
- excel
- kaggle

