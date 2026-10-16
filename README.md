# 📊 Power BI & Data Analysis Assignment Portfolio

This repository contains data analysis tasks, dataset cleanups, and Power BI report visualizations completed as part of my data analytics coursework. The project demonstrates skills in data modeling, DAX measure creation, Power Query transformation, and interactive report building.

---

## 📁 Repository Structure & Projects

### 1. Amazingcart Dataset (`Amazingcart.xlsx`)
* **Sheets Included:** `ListOfOrders`, `OrderBreakdown`
* **Key Tasks & Visualizations:**
  * **Clustered Column Chart:** Built to analyze and display the countries with the highest order placements (led by France, Germany, and the United Kingdom).
  * **Order Breakdown Analysis:** Explored sales, profit, quantity, and discount metrics across product categories and sub-categories.

### 2. Customer Transactions (`Customer_Data.xlsx`)
* **Key Tasks & Visualizations:**
  * **Line Chart:** Visualized the count of orders received per date over a continuous timeline to identify seasonal trends and peak order days.
  * **Calculated Columns:** Created custom DAX columns and Power Query custom columns to compute total prices by multiplying quantity by unit price.

### 3. Global Employee Layoffs (`Employee_Layoffs.csv`)
* **Key Tasks & Visualizations:**
  * **Pie / Donut Chart:** Visualized global layoff distributions by location, utilizing data cleaning techniques to unify location casing (e.g., *Bengaluru*, *SF Bay Area*) and filtering top hubs using "Top N" logic.

---

## 📐 DAX Measures & Formulas Reference

Below are the key DAX measures implemented across the datasets for reporting and analysis:

* **Total Sales:**
  ```dax
  Total Sales = SUM('OrderBreakdown'[Sales])
