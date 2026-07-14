# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and Hyperliquid historical trading data. The objective is to identify patterns between market sentiment and trader performance, discover trading behavior trends, and provide actionable business insights.

---

## Objectives

- Analyze trader performance under different market sentiment conditions.
- Merge the Fear & Greed Index with historical trading data.
- Perform data cleaning and feature engineering.
- Conduct exploratory data analysis (EDA).
- Generate business insights and recommendations.

---

## Dataset

### 1. Bitcoin Fear & Greed Index

- Date
- Timestamp
- Fear & Greed Value
- Classification

### 2. Hyperliquid Historical Trading Data

- Account
- Coin
- Execution Price
- Trade Size
- Side
- Closed PnL
- Fee
- Timestamp
- Transaction Details

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Workflow

1. Data Loading
2. Data Understanding
3. Data Cleaning & Feature Engineering
4. Dataset Merge
5. Exploratory Data Analysis (EDA)
6. Pattern Discovery
7. Business Recommendations

---

## Key Findings

- Successfully merged market sentiment with historical trading data.
- No missing values or duplicate records were found in the original datasets.
- Only six trades could not be matched because the Fear & Greed dataset did not contain data for one trading date.
- Trading activity varied across different weekdays and hours.
- Different market sentiment categories showed different trading characteristics.

---

## Project Structure

```
Primetrade_AI_Assignment/
│
├── data/
├── notebooks/
│   └── analysis.ipynb
├── report/
│   └── Final_Report.pdf
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone or download the project.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open

```
notebooks/analysis.ipynb
```

4. Run all notebook cells from top to bottom.

---

## Submitted By

Naiyar Alam

AI Internship Assignment
