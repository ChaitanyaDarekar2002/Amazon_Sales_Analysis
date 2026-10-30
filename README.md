# 📊 Amazon Sales Analysis – Power BI Dashboard

An interactive, multi-page **Power BI** dashboard that analyzes Amazon sales records from **2010 to 2016** across regions, product categories, order priorities, and sales channels (online vs. offline).

<img width="1542" height="739" alt="image" src="https://github.com/user-attachments/assets/0a2dd5b1-d191-4b3a-bf1c-421f341e4b06" />


---

## 🎯 Project Objective

To turn raw sales transactions into clear, decision-ready insights by answering questions such as:

- Which **regions** and **countries** generate the most revenue?
- Which **product categories** are the most (and least) profitable?
- How do **online vs. offline** channels compare in units, revenue, and cost?
- How do sales and orders trend **over time**?
- How are orders distributed by **priority level** (C / H / L / M)?

---

## 📈 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Units Sold | **513K** |
| Total Revenue | **137.35M** |
| Total Cost | **93.18M** |
| Total Profit | **44.17M** |
| Total Unit Price | 27.68K |
| Total Unit Cost | 19.10K |
| Overall Profit Margin | **≈ 32%** (Profit ÷ Revenue) |

---

## 🖼️ Dashboard Pages

### Page 1 – Cost, Priority & Channel Breakdown

<img width="1542" height="739" alt="image" src="https://github.com/user-attachments/assets/5bbda330-bccd-49da-ae8b-8465409e5091" />


- World map showing sales distribution by country
- Stacked bar: item types by **order priority** (H, L, M, C)
- Region-wise **sum of unit price** table
- Stacked column: **Offline vs. Online** sales by item type
- Funnel chart: **total cost by item type** (Office Supplies, Household and Cosmetics lead)

### Page 2 – Trends & Revenue Mix

<img width="1557" height="746" alt="image" src="https://github.com/user-attachments/assets/94dc0bea-020f-4920-a8df-f982e2b3bd57" />


- Time-series line chart showing sales trend across 2010–2017
- Donut chart: **revenue share by item type** (Cosmetics 36.6M, Office Supplies 30.59M, Household 29.89M)
- Clustered column: **region × order priority**
- Donut chart: **revenue by channel** – Offline 57.59% (79.09M) vs. Online 42.41% (58.25M)

### Page 3 – Regional Revenue, Profit & Units
![Page 3](screenshots/dashboard-3.png)

- **Revenue by region** – Sub-Saharan Africa (40M), Europe (33M), Asia (21M)
- **Profit by item type** – Cosmetics (14.56M) leads, followed by Household (7.41M) and Office Supplies (5.93M)
- Donut charts for **cost by channel** and **units sold by channel**

---

## 🔍 Key Insights

1. **Sub-Saharan Africa and Europe** together contribute over half of total revenue (≈ 73M of 137M).
2. **Cosmetics** is the top profit driver: ≈ 14.56M profit, about one-third of total profit.
3. **Office Supplies** has high revenue (30.59M) but a low profit (5.93M), a margin of roughly 19%, compared with ≈ 40% for Cosmetics.
4. The **top 3 categories** (Cosmetics, Office Supplies, Household) account for roughly 70% of revenue.
5. **Offline sales** lead online in revenue (57.6%), cost (58.1%) and units sold (54.0%).
6. **Fruits, Meat and Snacks** are the lowest-performing categories by profit.

> Insights are derived from the visuals in this dashboard; verify against the source data before using them for business decisions.

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** – data modeling and visualization
- **Power Query** – data cleaning and transformation
- **DAX** – calculated measures (Revenue, Cost, Profit, Margin, etc.)
- Interactive **year slicers** (2010–2016), cross-filtering between visuals, and a custom dark-glass UI theme

---

## 📁 Repository Structure

```
├── Amazon_Sales_Analysis.pbix     # Power BI dashboard file
├── data/
│   └── sales_data.csv             # Dataset (add your source file here)
├── screenshots/
│   ├── dashboard-1.png
│   ├── dashboard-2.png
│   └── dashboard-3.png
└── README.md
```

---

## 🚀 How to Use

1. Clone the repository
   ```bash
   git clone https://github.com/ChaitanyaDarekar2002/<your-repo-name>.git
   ```
2. Open `Amazon_Sales_Analysis.pbix` in **Power BI Desktop**
3. If prompted, update the data source path under **Transform data → Data source settings**
4. Use the **year slicers** and click on any chart element to cross-filter the dashboard

---

## 📚 Dataset

Sales records containing the following fields: Region, Country, Item Type, Sales Channel (Online/Offline), Order Priority, Order Date, Units Sold, Unit Price, Unit Cost, Total Revenue, Total Cost and Total Profit.


---

## 👤 Author

**Chaitanya Darekar**
Data Analyst | SQL • Python • Power BI • Excel • Tableau

- 🔗 [LinkedIn](https://www.linkedin.com/in/chaitanyadarekar02)
- 💻 [GitHub](https://github.com/ChaitanyaDarekar2002)
- 🌐 [Portfolio](https://chaitanyadarekar2002.github.io)

---

⭐ If you found this project useful, consider giving the repo a star!
