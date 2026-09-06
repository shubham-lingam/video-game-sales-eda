# Video Game Sales — Exploratory Data Analysis

## Project Overview

The video game industry has evolved significantly over the years, driven by changes in gaming platforms, consumer preferences, genres, publishers, and regional markets.

This project performs an Exploratory Data Analysis (EDA) of historical video game sales data to identify important market trends, understand commercial performance, and uncover differences in regional gaming preferences.

The analysis was developed using **Python, Pandas, NumPy, and Matplotlib** in a Kaggle Notebook.

---

## Business Objective

The objective of this project is to transform historical video game sales data into meaningful business insights.

The analysis focuses on:

- Historical global sales trends
- Platform performance
- Genre performance
- Publisher performance
- Best-selling individual games
- Regional gaming preferences

---

## Business Questions

This project answers six key business questions:

1. How have global video game sales changed over time?
2. Which gaming platforms have generated the highest global sales?
3. Which video game genres generate the highest global sales?
4. Which publishers have the strongest global sales performance?
5. Which games are the best-selling titles globally, and what do they have in common?
6. How do regional gaming preferences differ across major markets?

---

## Dataset

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

## Data Cleaning

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

# Key Findings

## 1. Peak Sales Year

**2008** was the strongest year in the dataset, with:

**678.90 million units**

The Top 5 years were:

| Year | Global Sales |
|---:|---:|
| 2008 | 678.90M |
| 2009 | 667.30M |
| 2007 | 611.13M |
| 2010 | 600.45M |
| 2006 | 521.04M |

### Business Insight

The strongest sales years were concentrated between **2006 and 2010**, indicating a particularly successful period for the historical video game market represented in the dataset.

---

## 2. Leading Gaming Platform

The **PS2** generated the highest cumulative global sales:

**1,255.64 million units**

Top-performing platforms included:

- PS2 — 1,255.64M
- X360 — 979.96M
- PS3 — 957.84M
- Wii — 926.71M
- DS — 822.49M

### Business Insight

The PS2 demonstrated the strongest cumulative platform performance in the dataset, showing the importance of a large user base, long platform lifecycle, and strong game library.

---

## 3. Highest-Selling Genre

**Action** was the highest-selling genre:

**1,751.18 million units**

This demonstrates strong historical commercial demand for Action games.

### Business Insight

Action games generated the strongest overall sales performance, making the genre an important category when analyzing historical gaming demand.

---

## 4. Leading Publisher

**Nintendo** ranked first among publishers:

**1,786.56 million units**

Nintendo also demonstrated exceptional individual-title performance, publishing **all 10 of the best-selling games** in the dataset.

### Business Insight

Nintendo's strong performance demonstrates the value of established franchises, recognizable intellectual property, and successful platform ecosystems.

---

## 5. Best-Selling Games

The Top 10 individual games generated a combined:

**369.39 million units**

Among the Top 10:

- Wii appeared in **5 titles**
- NES appeared in **2 titles**
- GB appeared in **2 titles**
- DS appeared in **1 title**
- Nintendo published **all 10 titles**

### Business Insight

The concentration of Nintendo titles among the best-selling games highlights the commercial strength of major franchises and successful platform ecosystems.

---

## 6. Regional Market Differences

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

### Business Insight

Japan showed a distinct preference for **Role-Playing games**, while Action was the leading genre across the other major regional markets.

This highlights the importance of understanding regional consumer preferences when developing and marketing video games.

---

# Key Business Insights

1. **2008 was the strongest sales year**, generating approximately **678.90 million units** in global sales.

2. **PS2 was the highest-performing gaming platform**, with cumulative global sales of approximately **1,255.64 million units**.

3. **Action was the highest-selling genre**, generating approximately **1,751.18 million units**.

4. **Nintendo was the leading publisher**, with approximately **1,786.56 million units** in global sales.

5. Nintendo published **all Top 10 best-selling games** in the dataset.

6. **North America represented the largest regional market**, accounting for approximately **49.27% of total regional sales**.

7. Regional gaming preferences differed significantly, with **Japan favoring Role-Playing games** while Action dominated other major markets.

---

# Business Recommendations

## 1. Focus on High-Demand Genres

Action games have demonstrated strong historical demand and represent an important commercial category.

However, genre selection should also consider regional preferences and current market trends.

## 2. Consider Platform Performance

Historical platform sales can provide useful insights when evaluating game development and distribution strategies.

Successful platforms often benefit from strong user bases, extensive game libraries, and recognizable franchises.

## 3. Build Strong Intellectual Properties

Nintendo's dominance among the best-selling games demonstrates the potential value of recognizable franchises and strong intellectual properties.

Companies can benefit from developing long-term franchises and building strong customer loyalty.

## 4. Adopt Regional Strategies

Regional differences, particularly Japan's stronger Role-Playing performance, suggest that localized marketing and product strategies can be valuable.

Game developers and publishers should consider regional preferences when planning product launches.

## 5. Use Historical Trends

Historical sales patterns can help businesses understand market cycles and support future demand forecasting when combined with current market information.

Historical data alone should not be used to predict future market performance.

---

# Tools & Technologies

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Kaggle Notebook**

---

# Notebook

The complete analysis is available in:

`Video_Game_Sales_EDA.ipynb`

The notebook contains:

- Data understanding
- Data cleaning
- Missing-value analysis
- Exploratory data analysis
- Six business questions
- Data visualizations
- Business insights
- Recommendations
- Conclusion

---

# Skills Demonstrated

`Python` `NumPy` `Pandas` `Matplotlib` `Data Cleaning` `Missing Value Analysis` `Exploratory Data Analysis` `Data Visualization` `Trend Analysis` `Regional Analysis` `Business Insights` `Data Storytelling`

---

# References

## Dataset

Kaggle — Video Game Sales Dataset

## Documentation

NumPy Documentation

Pandas Documentation

Matplotlib Documentation

---

# Repository Structure

```text
video-game-sales-eda/
│
├── Video_Game_Sales_EDA.ipynb
├── README.md
└── dataset/
    └── README.md
```
---
# Author

## L Shubham

# Data Analyst | Python | SQL | Power BI | Excel | Tableau | Data Visualization | Business Intelligence

GitHub: https://github.com/shubham-lingam

LinkedIn: https://www.linkedin.com/in/shubham-lingam

If you found this project useful, consider giving the repository a star.
