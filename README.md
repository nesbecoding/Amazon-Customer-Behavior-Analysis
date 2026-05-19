# Amazon Customer Behavior Analysis

An exploratory data analysis of Amazon customer survey data, covering purchasing habits, demographics, product preferences, review reliance, and satisfaction.

---

## Overview

This project digs into what drives Amazon customers' decisions, from who they are and when they shop, to what they buy, how they find it, and how satisfied they end up. The goal is to better know the customers 

## Dataset

**Amazon Customer Behavior Survey** — available on [Kaggle](https://www.kaggle.com/datasets/swathiunnikrishnan/amazon-consumer-behaviour-dataset).

Download the CSV and place it in the same folder as the notebook before running.


## Analysis Sections

| # | Section | What it covers |
|---|---|---|
| 1 | Data Loading | Load the CSV into a DataFrame |
| 2 | Initial Exploration | Shape, types, basic statistics |
| 3 | Data Cleaning & Feature Engineering | Handle nulls; create Age Category, Hour, Time Category |
| 4 | Customer Demographics | Gender split, age distribution, shopping time of day, purchase frequency |
| 5 | Purchase Category Preferences | Category breakdown by gender and age group |
| 6 | Review Reliance & Satisfaction | How reviews are used and their correlation with satisfaction |
| 7 | Service Appreciation & Improvement Areas | What customers love and what they want fixed |
| 8 | Search Behavior & Cart Abandonment | How products are discovered and why purchases are abandoned |
| 9 | Conclusions | Summary table of key findings |

## Key Findings

- **~60% of customers are female**, and most fall in the Adult (25–39) or Young Adult (18–24) range
- **~60% of purchases happen at night**, suggesting post-work browsing habits
- **Beauty & Personal Care and Clothing & Fashion** account for nearly 50% of female purchases
- **Young Adults rely on reviews more heavily** than Adults (33.3% vs 21.1%)
- **Product Recommendations** is the most appreciated Amazon feature
- **Customer service responsiveness** is the most requested area for improvement
- Customers who engage more with reviews report **higher shopping satisfaction**


## Requirements

```
pandas
matplotlib
seaborn
plotly
```

---

*Dataset: Amazon Customer Behavior Survey (Kaggle)*
