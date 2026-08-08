# 🎮 Video Game Sales — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Kaggle](https://img.shields.io/badge/Platform-Kaggle-blue)

## 📌 Project Overview

The video game industry has evolved significantly over the years, driven by changes in gaming platforms, consumer preferences, genres, publishers, and regional markets.

This project performs an Exploratory Data Analysis (EDA) of historical video game sales data to identify important market trends, understand commercial performance, and uncover differences in regional gaming preferences.

The analysis was developed using **Python, Pandas, NumPy, and Matplotlib** in a Kaggle Notebook.

---

## 🎯 Business Objective

The objective of this project is to transform historical video game sales data into meaningful business insights.

The analysis focuses on:

- Historical global sales trends
- Platform performance
- Genre performance
- Publisher performance
- Best-selling individual games
- Regional gaming preferences

---

## ❓ Business Questions

This project answers six key business questions:

1. How have global video game sales changed over time?
2. Which gaming platforms have generated the highest global sales?
3. Which video game genres generate the highest global sales?
4. Which publishers have the strongest global sales performance?
5. Which games are the best-selling titles globally, and what do they have in common?
6. How do regional gaming preferences differ across major markets?

---

## 📊 Dataset

The dataset contains **16,598 video game records** and 11 variables.

### Key Columns

| Column | Description |
|---|---|
| Rank | Overall ranking of the game |
| Name | Name of the video game |
| Platform | Gaming platform |
| Year | Release year |
| Genre | Game genre |
| Publisher | Game publisher |
| NA_Sales | Sales in North America |
| EU_Sales | Sales in Europe |
| JP_Sales | Sales in Japan |
| Other_Sales | Sales in other regions |
| Global_Sales | Global sales |

Sales values are measured in **millions of units**.

---

## 🧹 Data Cleaning

The dataset was inspected and cleaned before performing the analysis.

### Data Quality Findings

- **16,598 records**
- **11 columns**
- **271 missing values** in `Year`
- **58 missing values** in `Publisher`
- **0 duplicate records**

### Cleaning Approach

- Missing publisher values were replaced with **"Unknown"**.
- Missing release years were retained as `NaN` rather than being artificially imputed.
- Missing-year records were excluded only from time-based analysis.
- The `Year` column was converted to Pandas nullable integer format.
- Duplicate records were checked and none were found.

---

# 📈 Key Findings

## 1️⃣ Peak Sales Year

**2008** was the strongest year in the dataset, with:

> **678.90 million units**

The Top 5 years were:

| Year | Global Sales |
|---:|---:|
| 2008 | 678.90M |
| 2009 | 667.30M |
| 2007 | 611.13M |
| 2010 | 600.45M |
| 2006 | 521.04M |

---

## 2️⃣ Leading Gaming Platform

The **PS2** generated the highest cumulative global sales:

> **1,255.64 million units**

Top-performing platforms included:

- PS2 — 1,255.64M
- X360 — 979.96M
- PS3 — 957.84M
- Wii — 926.71M
- DS — 822.49M

---

## 3️⃣ Highest-Selling Genre

**Action** was the highest-selling genre:

> **1,751.18 million units**

This demonstrates strong historical commercial demand for Action games.

---

## 4️⃣ Leading Publisher

**Nintendo** ranked first among publishers:

> **1,786.56 million units**

Nintendo also demonstrated exceptional individual-title performance, publishing **all 10 of the best-selling games** in the dataset.

---

## 5️⃣ Best-Selling Games

The Top 10 individual games generated a combined:

> **369.39 million units**

Among the Top 10:

- Wii appeared in **5 titles**
- NES appeared in **2 titles**
- GB appeared in **2 titles**
- DS appeared in **1 title**
- Nintendo published **all 10 titles**

---

## 6️⃣ Regional Market Differences

North America represented the largest regional market:

| Region | Sales | Share |
|---|---:|---:|
| North America | 4,392.95M | 49.27% |
| Europe | 2,434.13M | 27.30% |
| Japan | 1,291.02M | 14.48% |
| Other Regions | 797.75M | 8.95% |

### Regional Genre Leaders

| Region | Top Genre | Sales |
|---|---|---:|
| North America | Action | 877.83M |
| Europe | Action | 525.00M |
| Japan | Role-Playing | 352.31M |
| Other Regions | Action | 187.38M |

Japan showed a distinct preference for **Role-Playing games**, while Action was the leading genre across the other major regional groups.

---

# 💡 Business Recommendations

Based on the analysis:

### 🎯 1. Focus on High-Demand Genres

Action games have demonstrated strong historical demand and represent an important commercial category.

### 🎮 2. Consider Platform Performance

Historical platform sales should be considered when making game development and distribution decisions.

### 🏆 3. Build Strong Intellectual Properties

Nintendo's dominance among the best-selling games demonstrates the potential value of recognizable franchises and strong intellectual properties.

### 🌍 4. Adopt Regional Strategies

Regional differences, particularly Japan's stronger Role-Playing performance, suggest that localized marketing and product strategies can be valuable.

### 📊 5. Use Historical Trends

Historical sales patterns can help businesses understand market cycles and support future demand forecasting when combined with current market information.

---

# 🛠️ Tools & Technologies

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Kaggle Notebook**

---

# 📓 Notebook

The complete analysis is available in:

**`Video_Game_Sales_EDA.ipynb`**

The notebook contains:

- Data understanding
- Data cleaning
- Exploratory analysis
- 6 business questions
- Visualizations
- Business insights
- Recommendations
- Conclusion

---

# 📚 References

- Kaggle — Video Game Sales Dataset
- NumPy Documentation
- Pandas Documentation
- Matplotlib Documentation

---

## 👤 Author

**L Shubham**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Tableau

📍 Pune, Maharashtra, India

---

⭐ If you found this project useful, consider giving the repository a star.
