# 🛒 Superstore Sales Performance Analysis

A data analysis project examining 4 years of U.S. retail sales data to uncover which regions, product categories, and individual products are driving profit — and which ones are losing money.

---

## 📌 Business Problem

A retail superstore had years of accumulated sales data but no clear visibility into its actual profitability. This project answers the key questions a business owner or manager needs to make smarter decisions:

- Which region is most profitable?
- Which products should we stop discounting?
- When does demand peak — and are we ready for it?
- Which customer segments deserve more attention?

---

## 📂 Dataset

- **Source:** [Kaggle — Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Size:** 9,993 transactions
- **Period:** 2019 – 2022
- **Fields:** Order Date, Region, Category, Sub-Category, Product Name, Sales, Profit, Discount, Quantity, Customer Segment

---

## 🛠️ Tools & Techniques

| Tool | Purpose |
|------|---------|
| Python | Core analysis language |
| Pandas | Data loading and manipulation |
| SQLite (via Python) | SQL queries on the dataset |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Google Colab | Development environment |

---

## 🧮 Analysis Performed

Seven SQL queries were written to answer specific business questions:

1. Total sales and profit by region
2. Top 10 most profitable products
3. Bottom 10 loss-making products
4. Monthly revenue and profit trends
5. Sales and profit by product category
6. Profit margin (%) by sub-category
7. Top 10 customers by revenue

---

## 📊 Visualizations

Five charts were produced:

- **Bar chart** — Sales & Profit by Region
- **Line chart** — Monthly Sales & Profit Trend (2019–2022)
- **Horizontal bar chart** — Top 10 Most Profitable Products
- **Horizontal bar chart** — Profit Margin by Sub-Category
- **Scatter/bubble chart** — Sales vs Profit by Category

---

## 🔍 Key Findings

- Total revenue of **$2.3M** over 4 years with only **$286K in profit** — a 12% margin heavily impacted by discounting
- The **West region** led in both sales and profit; the **South region** underperformed on margins despite reasonable sales volume
- **Technology** was the most profitable category; **Furniture** had strong sales but the lowest profit margins
- **Tables, Bookcases, and Supplies** operated at a **negative profit margin** — losses increased with every discounted sale
- A consistent **Q4 revenue spike** was identified every year — a seasonal pattern the business could better prepare for
- The **Consumer segment** had the most orders, but **Corporate and Home Office** customers had higher average order values

---

## 💡 Business Recommendations

1. **Stop discounting Tables, Bookcases, and Supplies** — the more units sold at current discount rates, the greater the loss
2. **Prioritize Technology marketing** — best margins, consistent demand, strong in the West and East
3. **Plan ahead for Q4** — pre-stock inventory and launch campaigns in September to maximize the seasonal peak
4. **Target Corporate and Home Office segments** — fewer customers but significantly higher spend per order

---

## 📁 Repository Structure

```
superstore-sales-analysis/
│
├── Superstore_Sales_Analysis.ipynb   # Full analysis notebook
└── README.md                         # Project overview (this file)
```

---

## 👩‍💻 About the Author

**Christine Obinga** — Data Analyst based in Kenya, specializing in Python, SQL, and data visualization. Helping businesses turn raw data into clear, actionable insights.

🌐 [Portfolio Website](https://sites.google.com/view/christineobinga) 

---

*This is Project 1 of an ongoing data analytics portfolio.*
