# 🛒 Online Retail Analysis Dashboard

This project is a comprehensive **B2B sales performance and customer behavior analysis** using real-world retail transaction data from a UK-based online store. It integrates deep data cleaning (in Python) with rich business insights (in Tableau), enabling decision-makers to understand key sales drivers, customer segments, and churn trends.

---

## 🔍 Project Goals

- Clean and prepare messy real-world data for reliable analysis.
- Identify patterns in **customer retention**, **churn**, and **purchase frequency**.
- Provide **category-wise and region-wise** sales insights.
- Enable **drill-down exploration** of key performance areas (returns, top customers, frequent buyers).
- Align business metrics with customer behavior to support decision-making.

- ---

## 🗃️ Dataset Info

- 📦 **Original Raw Data**: 541,909 rows × 8 columns  
- 🧪 **Cleaned Dataset (df2)**: 524,876 rows × 12 columns  
- 🔍 **Final Transaction Frame (df3)**: 523,959 rows × 12 columns  

➡️ **Total cell values handled during cleaning**:  
💡 **Over 5 million+ data points** processed (≈ 524K rows × 12 columns)

- **Source**: UCI Machine Learning Repository - [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Region**: Primarily UK, with customers from EU and other countries

---

## 🧹 Cleaning Process (Python)

- Removed all nulls & cancelled orders  
- Filtered to only positive quantities & prices  
- Created new columns for analysis (`TotalAmount`, time features)  
- Outlier removal using:
  - IQR (Unit Price)
  - Z-score (Quantity)  
- Final cleaned file used for Tableau

📄 See full steps: `Online Retail Analysis Python Report.pdf`

## 📊 Tableau Dashboard Overview

Dashboard includes interactive visuals:

- 📈 **Sales Trend** – Monthly revenue pattern  
- 📦 **Top Products** – Sorted by Total price  
- 🌍 **Country Heatmap** – Distribution analysis on different days  
- 📊 Histograms & Pie charts for categorical distributions  

🧠 Business-friendly interface with filter & drill-down options.

---

## 📌 Key Insights

- **November–December** show peak activity due to holiday sales.
- **United Kingdom** contributes >90% of revenue; Germany and Netherlands are next.
- Products with high unit prices show less volume movement.

---

📌 How to Use
🧭 Tableau Dashboard:
- Download the .twbx file from this GitHub repository
- Open it using Tableau Public (free) or Tableau Desktop
- Explore filters, visuals, and KPIs interactively
- Designed to be intuitive for managers and business users—no technical setup required

🐍 Python Analysis (on Google Colab):

- Download the provided Python Report (PDF) for a step-by-step explanation
- No need to install Python or download large data files
- All analysis, cleaning, and outlier handling were done on Google Colab with real-time code execution
- Ideal for understanding backend logic without technical complexity

---

📚 Reference

- A heartfelt thanks to Codebasics and their incredible YouTube series on the Online Retail project. While I built and customized the analysis and dashboard on my own, their content served as a great source of inspiration and direction during the early stages. I'm truly grateful for such accessible and insightful learning resources!
