# Cognitive Demand Sensing — Bullwhip Solver

## Reducing FMCG Forecast Error by 68% and Generating $470,146 Annual Holding Cost Savings Through ML Forecasting

---

## Business Problem

Traditional demand planning relies on 3-month moving averages built in Excel.
This approach is blind to seasonality, trend acceleration and external demand signals.

The result:
- Chronic stockouts during peak months (November +84% above average)
- Systematic under-forecasting bias of -20.1%
- $929,918 annual holding costs from oversized safety stock buffers
- Bullwhip effect amplifying demand volatility upstream through the supply chain

This project answers one question:
**How much forecast accuracy improvement is achievable by replacing Excel
with ML — and what is that improvement worth in dollars?**

---

## Solution

A multi-model FMCG demand forecasting system comparing 10 forecasting methods
from naive moving averages to ML — benchmarked using IBF industry standards.

---

## Results

| Metric | Naive Baseline | Prophet ML | Improvement |
|---|---|---|---|
| MAPE | 50.8% | 15.79% | 68% reduction |
| MAE | $17,760/month | $9,922/month | 44% reduction |
| Bias | -20.1% | -6.96% | 65% reduction |
| Safety Stock | 16,172 units | 7,996 units | 50% reduction |
| Annual Holding Cost | $929,918 | $459,772 | $470,146 saved |

---

## Dataset

**Source:** Kaggle FMCG Retail Sales Dataset
**Size:** 9,789 transactions | 18 columns | 4 years (2015-2018)
**Key columns:** Order Date, Ship Date, Category, Sub-Category,
Region, Sales

**Download:** https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

Place downloaded file at: Downloads/archive/train.csv

---

## Project Structure
