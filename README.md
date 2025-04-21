# 🛒 Large-Scale Online Retail Sales Data Analysis

This project focuses on performing large-scale data analysis on **online retail sales data**. I begin by analyzing **5 million transactions** using **pandas**, and then demonstrate how we can significantly speed up the analysis using **[fireducks](https://github.com/duckdblabs/fireducks)** — a compiler-accelerated dataframe library that is fully compatible with the pandas API.

---

## 🚀 Project Goals

- Load and explore large retail sales datasets.
- Perform data cleaning, transformation, and aggregation.
- Compare performance and results using:
  - Standard **pandas**
  - **fireducks** for high-performance, scalable analysis

---

## 📂 Dataset

The dataset consists of **5 million+ online retail transactions**, typically containing:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country
---

## 🔧 Requirements

Install the dependencies:

```bash
pip install pandas
pip install fireducks
