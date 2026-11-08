# 🛒 Amazon Product Reviews Sentiment Analysis — Power BI

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Query_View-blue?style=for-the-badge)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-SYNTECXHUB-orange?style=for-the-badge)

## 📌 Project Overview
This repository contains **Task 4**, the final project of my **Data Analytics Internship at SYNTECXHUB**. 

The goal of this project is to analyze customer feedback on Amazon products by classifying unstructured review sentiment and evaluating performance metrics across product categories and brands using **Power BI** and **DAX**.

---

## 🛠️ Key Features & Technical Highlights

- **Sentiment Classification Engine:** Built custom DAX logic to categorize reviews into `Positive`, `Neutral`, and `Negative` sentiments based on star ratings and feedback indicators.
- **Dynamic KPI Calculations:** Developed core DAX measures (`CALCULATE`, `DIVIDE`, `COUNTA`) to calculate total reviews, positive/negative review counts, and positive sentiment percentages dynamically.
- **DAX Query View Validation:** Executed evaluation queries (`EVALUATE`, `SUMMARIZE`, `ORDER BY`) in Power BI’s DAX Query View to debug, validate brand performance outputs, and optimize measure syntax prior to report deployment.
- **Interactive Visual Dashboard:**
  - Top-level **KPI Cards** for high-level executive metrics.
  - **Donut Chart** illustrating sentiment percentage distribution across sub-categories.
  - **Stacked Bar Chart** tracking customer sentiment split across 1-star through 5-star ratings.
  - **Interactive Detail Table** enabling real-time cross-filtering and line-by-line review exploration.

---

## 🧮 DAX Measures Implemented

### 1. Total Reviews
```dax
Total Reviews = COUNT('anaz====='[Review Rating])
