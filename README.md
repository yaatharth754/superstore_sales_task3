# 📊 Sales Performance Dashboard (Power BI)

## 📌 Project Overview

This project presents an **interactive Sales Performance Dashboard** built using **Power BI**.
The dashboard analyzes sales data to provide insights into revenue, orders, profit margins, shipping performance, and product trends.

It helps businesses understand **sales performance across categories, regions, and time** to support better decision-making.

---

## 🛠 Tools & Technologies

* **Power BI** – Data visualization and dashboard creation
* **DAX (Data Analysis Expressions)** – Creating calculated measures
* **CSV Dataset** – Cleaned sales data

---

## 📂 Project Files

* `Sales_Performance_Dashboard.pbix` – Power BI dashboard file
* `cleaned_data.csv` – Cleaned dataset used for analysis
* `README.md` – Project documentation
* `dashboard.png` – Screenshot of the dashboard

---

## 📈 Key Metrics (DAX Measures)

```DAX
Total Revenue = SUM(cleaned_data[Sales])

Total Orders = DISTINCTCOUNT(cleaned_data[Order ID])

Average Order Value = DIVIDE([Total Revenue], [Total Orders])

Profit Margin = DIVIDE(SUM(cleaned_data[Profit]), SUM(cleaned_data[Sales]))

Avg Shipping Days = AVERAGE(cleaned_data[Shipping Days])
```

---

## 📊 Dashboard Features

The dashboard includes the following visuals:

* **KPI Cards**

  * Total Revenue
  * Total Orders
  * Average Order Value
  * Profit Margin
  * Average Shipping Days

* **Visual Charts**

  * Sales by Category
  * Sales by Region
  * Monthly Sales Trend
  * Top Sub-Categories by Sales

* **Interactive Filters**

  * Region
  * Category
  * Year

These filters allow users to dynamically explore the data.

---

## 📷 Dashboard Preview

(Add your screenshot here)

```
![Dashboard Preview](dashboard.png)
```

---

## 🎯 Key Insights

* Technology category generated the **highest revenue**.
* Certain regions contributed more significantly to total sales.
* Monthly trends help identify **seasonal demand patterns**.
* Shipping time averages help evaluate **logistics efficiency**.

---

## 🚀 How to Use

1. Download the repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Load the dataset if prompted.
4. Interact with filters to explore insights.

---

## 📚 Learning Outcomes

This project helped develop skills in:

* Data cleaning and preparation
* DAX measure creation
* Interactive dashboard design
* Business data visualization
* Analytical storytelling



