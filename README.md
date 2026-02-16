# 📊 Task 7 – Mini Dashboard (Power BI)

## 📌 Internship Task
This project is part of the **Data Analyst Internship Program**.

The objective of this task is to design an interactive business dashboard using Power BI to analyze sales and profit performance across different regions and product categories.

---

## 📂 Dataset Used
Global Superstore Dataset

The dataset contains global retail transaction data including:

- Order Date
- Sales
- Profit
- Category
- Sub-Category
- Region
- Segment
- Quantity
- Shipping Cost
- Customer Details

---

## 🛠 Tools & Technologies

- Power BI Desktop
- Microsoft Excel (Preprocessing)
- DAX (Data Analysis Expressions)

---

## 🔎 Data Preparation

Before importing into Power BI:

- Checked missing values in Excel
- Verified date formats
- Ensured Sales & Profit were numeric
- Removed duplicate or blank records

Dataset was then imported into Power BI for visualization.

---

## 🧮 Calculated Measures (DAX)

Created key business metrics:

**Total Sales**
```DAX
Total Sales = SUM(global_superstore[Sales])

Total Profit = SUM(global_superstore[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Sales])
