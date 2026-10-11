# 📊 Sales Data Analysis & Predictive Modeling
*AI Academia — Python with Data Science Internship Capstone*

> An end-to-end data science pipeline analyzing retail sales trends, discovering high-value products, and predicting real-time cart values using machine learning.

---

## 🚀 Project Overview
This repository contains a comprehensive analysis of retail sales data designed to identify seasonal revenue trends, evaluate regional product performance, and deploy predictive AI models. The project transitions from foundational exploratory data analysis (EDA) to advanced machine learning classification and regression.

## 🛠️ Tools & Technologies
| Category | Libraries / Frameworks |
| :--- | :--- |
| **Data Manipulation** | `Pandas`, `NumPy` |
| **Data Visualization** | `Matplotlib`, `Seaborn` |
| **Statistical Analysis** | `SciPy` |
| **Machine Learning** | `Scikit-learn` (Random Forest, Gradient Boosting) |
| **Model Persistence** | `Joblib` |

## 📦 Dataset Profile
- **Source:** Superstore Retail Dataset
- **Volume:** 9,994 transactions (Rows) x 21 metrics (Columns)
- **Timeframe:** 2014 – 2017
- **Scope:** Captures order metrics, gross sales, net profit, discount depth, customer segments, and regional product categories across the United States.

## 💡 Key Business Findings
1. **The Technology Revenue Engine:** The Technology category generates the most total revenue, exceeding **$800,000** (roughly 36.4% of total gross sales).
2. **Q1 Checkout Spikes:** March yields the highest average sales per individual order at approximately **$295**, well above the annual baseline average of $229.86.
3. **The Whale Effect:** The Canon imageCLASS 2200 Advanced Copier dominates top product sales (**$61,599.82**), while basic office consumables sit at the bottom ($1.62), confirming that gross revenue relies heavily on high-margin enterprise hardware.
4. **Conquering Seasonality:** Non-linear Random Forest modeling successfully resolved seasonal market volatility, boosting our regression R-squared score to **0.7198** (compared to a linear baseline failure of -30.20).
5. **High-Value Cart Indicators:** Our Gradient Boosting Classifier achieved **91.70%** accuracy, mathematically proving that net profit margin and discount depth are the definitive indicators separating VIP carts from standard orders.

## ⚙️ How to Run Locally
To replicate this analysis or test the interactive AI Prediction Terminal on your own machine:

1. Clone this repository and ensure all files are in your working directory.
2. Install the required dependencies in your terminal:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy joblib
