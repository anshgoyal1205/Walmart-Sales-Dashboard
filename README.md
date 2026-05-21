# 🛒 Walmart Sales Dashboard
> An interactive multi-page Power BI dashboard analysing Walmart sales performance across regions, salespersons, product categories, and customer segments.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

The **Walmart Sales Dashboard** is a 4-page interactive Power BI report built to analyse retail sales performance across regions, salespersons, product categories, and customer demographics. The dashboard provides a clear view of revenue trends, target achievement, top/bottom performers, and customer behaviour.

---

## 📁 Dashboard Pages

| # | Page | Description |
|---|------|-------------|
| 1 | **Home** | Overall KPI summary, Sales by Region, Sales by Category, Sales by City (Map), Sales by Month |
| 2 | **Performance** | Top 5 Sales Persons by Sales, Bottom 5 by Target Difference, Sales vs Target table, Sales & Target by Region |
| 3 | **Sales Person** | Sales Person breakdown by Sales and Region (small multiples) |
| 4 | **Customer** | Sales by Customer Age Group, Sales by Region, Sales by ProductCategory, Sales by Month |

---

## 🗃️ Data Model

The report uses the following tables:

**Fact Table:**
- `SalesTable` — Sale ID, Date, City, Region, Revenue, Units Sold, Unit Price, Sales Target, Target Diff, Salesperson, Supplier, Product Name, Product Category, Customer Age, Customer Age Group, Payment Mode, Feedback Score

**Dimension Tables:**
- `SalesPersonTable` — ID, SalesPerson, Education, Contact Number
- `CategoryTable` — ID, ProductCategory, List of Product
- `SupplierTable` — ID, Company Name, Contact Number

---

## 📊 KPI Overview (All Pages)

| Metric | Value |
|--------|-------|
| Total Sales | $1.71M |
| Total Orders | 300 |
| Quantity Sold | 3.10K |
| Target Achieve % | 91.75% |
| Avg Rating | 3.68 |

---

## 🔧 Tools & Technologies

- **Power BI Desktop**
- **Power Query (M)** — Data transformation and cleaning
- **Slicers** — ProductCategory, SalesPerson, Region, Product Name
- **Visuals used** — Bar charts, Donut chart, Area/Line chart, Map visual, Small multiples, Table

> Note: This dashboard focuses on visual storytelling using Power Query transformations and built-in Power BI aggregations. Separate DAX measures were not created — calculations like Target Achieve % and Target Diff are derived columns in the data model.

---

## ✨ Key Features

- **4-Page Navigation** — Sidebar buttons for Home, Performance, Sales Person, Customer
- **Global Slicers** — Filter entire dashboard by ProductCategory, SalesPerson, Region, Product Name
- **Map Visual** — Sales by City plotted on US map using Bing Maps
- **Small Multiples** — Sales Person by Region shown as individual mini charts per salesperson
- **Top & Bottom Analysis** — Top 5 performers by sales + Bottom 5 by target difference
- **Sales vs Target Table** — Detailed salesperson-level comparison with totals

---

## 📊 Key Business Insights

- 💰 **Total Sales: $1.71M** against a sales target — achieving **91.75%** of target
- 🏆 **Top Sales Person: Grace** — $306,860 in sales
- ⚠️ **All salespersons are below their individual targets** — highest gap at Grace (-$29K)
- 🛍️ **Clothing is the top product category** at **23.74%** of total sales
- 🏠 **Home Appliances** close second at **23.3%**
- 🗺️ **West region** generates highest sales (~$500K+)
- 👴 **Elder customer age group** contributes highest sales (~$750K)
- 📅 **March recorded peak sales** — visible spike in Sales by Month chart
- 📉 **April recorded lowest sales** — sharp drop after March peak
- ⭐ **Average customer rating: 3.68** out of 5

---

## 📂 Dataset Details

| Table | Key Fields |
|-------|------------|
| SalesTable | Revenue, Units Sold, Sales Target, Target Diff, Region, City, Date |
| SalesPersonTable | SalesPerson name, Education, Contact |
| CategoryTable | ProductCategory, List of Products |
| SupplierTable | Company Name, Contact |

- **Total Orders: 300**
- **Regions: 4** (West, South, North, East)
- **Product Categories: 5** (Clothing, Home Appliances, Toys, Electronics, Furniture)
- **Customer Age Groups: 3** (Elder, Senior Citizen, Young)
- **Salespersons: 8** (Grace, Frank, David, Alice, Charlie, Helen, Eva, Bob)

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop** (free download from Microsoft)
3. Use the **sidebar buttons** to navigate between pages
4. Use the **slicers** on the left to filter by Category, SalesPerson, Region, or Product
5. Hover over charts for detailed tooltips
6. Click on any visual element to cross-filter other visuals on the page

---

## 👤 Author

**Ansh Goyal**
📧 anshgoyal1205@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/ansh-goyal-180b19212)

