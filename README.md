# Diwali Sales Analysis

An exploratory data analysis (EDA) project analyzing Diwali sales transactions to identify customer demographics, purchasing behavior, and revenue drivers.

---

## 📌 Project Overview
The objective of this project is to clean, transform, and analyze festive retail transaction data to help businesses understand customer buying patterns and optimize marketing and inventory strategies.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:**
  * `pandas` & `numpy` – Data cleaning, wrangling, and aggregation
  * `matplotlib` & `seaborn` – Statistical data visualization

---

## 🧹 Data Cleaning & Preprocessing
* Removed redundant empty columns (`Status`, `unnamed1`).
* Handled null values in the `Amount` feature.
* Cast numerical fields to appropriate data types (`Amount` converted to integer).

---

## 🔍 Key Insights & Findings
* **Gender & Purchasing Power:** Female buyers outnumber male buyers significantly and account for ~70% of total sales revenue.
* **Age Demographics:** The primary customer base falls within the **26–35 years** age bracket, driving the largest volume of orders.
* **Marital Status:** Married women represent the single largest demographic contributing to sales.
* **Top Contributing States:** The highest sales and order counts originate from **Uttar Pradesh**, **Maharashtra**, and **Karnataka**.
* **Occupations:** Professionals working in the **IT Sector**, **Healthcare**, and **Aviation** represent the top spenders.
* **Product Categories:** The most popular purchasing categories by total sales volume are **Food**, **Clothing & Apparel**, and **Electronics & Gadgets**.

---

## 📈 Conclusion & Business Recommendations
Marketing campaigns and holiday promotional offers should primarily target **married women aged 26–35** residing in **Uttar Pradesh, Maharashtra, and Karnataka** working in corporate/healthcare sectors, with a strong focus on bundling **Food, Apparel, and Electronics** products.

---

## 📂 Repository Structure
```text
├── Diwali Sales Data.csv        # Raw dataset
├── diwali sales analysis.ipynb  # Jupyter notebook containing EDA and visualizations
└── README.md                    # Project documentation
