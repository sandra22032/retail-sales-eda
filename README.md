# 🛒 Retail Store Sales — Exploratory Data Analysis

## Overview
An end-to-end EDA project on a retail store sales dataset containing 
12,575 transactions across 8 product categories from 2022–2024.

## Objectives
- Understand revenue distribution across product categories
- Identify sales trends over time
- Analyse the impact of discounts on customer spending
- Compare Online vs In-store channel performance

## Dataset
- 12,575 rows × 11 columns
- Source: [Kaggle / wherever you got it]
- Key columns: Category, Total Spent, Payment Method, 
  Location, Transaction Date, Discount Applied

## Tools & Libraries
Python · pandas · numpy · matplotlib · seaborn

## Key Findings
1. Revenue is evenly spread across all 8 categories (~$180K–$210K each)
2. Discounts have virtually no impact on basket size ($129.95 vs $130.49)
3. Online and In-store channels perform almost equally (~$760K each)
4. Payment methods are split almost equally three ways (Cash 34%, 
   Digital Wallet 33%, Credit Card 33%)
5. Monthly sales show high volatility with no clear seasonal pattern

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `RetailSales_EDA.ipynb` in Jupyter Notebook or JupyterLab
