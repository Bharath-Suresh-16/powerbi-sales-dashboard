# 🧾 Sales Dashboard Analysis | Power BI

This project is a dynamic and interactive **Sales Dashboard** built using **Power BI**. It visualizes key sales performance indicators (KPIs) such as total sales, sales by platform, top-selling products, regional performance, and sales growth over time.

---

## 📊 Dashboard Overview

![Sales Dashboard Screenshot](dashboard-screenshot.png)

---

## 📌 Key Features

- **Total Sales KPIs** displayed in currency format
- **Top 5 Best-Selling Products** by sales value
- **Sales Distribution by Platform** (Brick & Mortar vs E-Commerce)
- **Top Regions by Sales** using a pie chart
- **Sales Growth Trendline** over months
- **Geographic Sales Map** to visualize location-based sales
- **Category & Year Filters** for dynamic data exploration

---

## 🧰 Tools & Technologies Used

- **Power BI Desktop**
- **Power Query** – for data cleaning and transformation
- **DAX (Data Analysis Expressions)** – for creating measures and calculated columns
- **Data Modeling** – star schema with fact and dimension tables

---

## 🧩 Data Model Structure

- `fact_sales_monthly`: Net sales amount, quantity, customer/product codes, and date
- `dim_customer`: Customer details (channel, platform, market)
- `dim_product`: Product hierarchy (category, division, segment, variant)
- `dim_market`: Market segmentation (region, sub-zone)

---

## 📂 Dataset

> The dataset used in this project is synthetic and structured to simulate realistic sales data across regions and platforms. It is intended for educational and demonstration purposes only.

---

## ▶️ How to View

1. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Clone or download this repository
3. Open the file `Sales_Dashboard.pbix` in Power BI Desktop
4. Interact with slicers, charts, and maps

---

## 📈 Learning Outcome

This project demonstrates practical knowledge of:
- Building KPI-driven dashboards
- Designing effective data models
- Writing DAX formulas
- Creating filters and slicers for dynamic dashboards
- Visual storytelling using charts and maps

---

## 📬 Contact

Created by **Bharath**  
For any queries or collaborations: [LinkedIn]((https://www.linkedin.com/in/bharath-s-data))

