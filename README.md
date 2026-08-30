# 📊 SN Corp — Shipment Orders & Sales Analytics Dashboard

A Power BI dashboard built to analyze **4,115 shipment orders** across customers, products, regions, countries, categories, and shipping modes.

The project converts raw Excel order data into an interactive business intelligence dashboard covering **sales performance, profitability, customer analysis, product performance, geographic distribution, and order trends**.

---

## 📸 Dashboard Preview

![SN Corp Dashboard](screenshots/dashboard-overview.png)

---

## 🎯 Project Objective

The objective of this project was to transform raw shipment-order data into a business-focused Power BI dashboard that can be used to:

- Monitor overall sales, cost, and profit
- Identify high-performing regions and countries
- Understand customer and segment performance
- Compare product categories and sub-categories
- Analyze shipping-mode usage
- Track order volume over time
- Identify areas with stronger profitability

---

## 📌 Key Metrics

| KPI | Value |
|---|---:|
| Total Sales | **1.27M** |
| Total Cost | **640.6K** |
| Total Profit | **627.0K** |
| Total Orders | **4,115** |
| Total Quantity | **15,420** |
| Customers | **792** |
| Countries | **15** |
| Products | **1,466** |
| Overall Profit Margin | **49.46%** |

> Profit margin is calculated as Total Profit / Total Sales.

---

## 🔍 Key Business Insights

### 🌍 Regional Performance

The **Central region** is the largest contributor to sales:

- Sales: **698.2K**
- Share of total sales: **55.09%**
- Profit: **345.2K**
- Orders: **2,233**

North and South contribute approximately **22.8%** and **22.1%** of sales respectively.

Despite having lower sales, the **South region has the highest profit margin at approximately 50.6%**, compared with 49.4% in Central and 48.4% in North.

**Business implication:** Central is the primary revenue market, while South shows relatively stronger profitability and could warrant further growth investment.

---

### 👥 Customer Segment Performance

The **Consumer segment** is the largest revenue contributor:

| Segment | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Consumer | 680.5K | 344.0K | 50.5% |
| Corporate | 378.6K | 181.3K | 47.9% |
| Home Office | 208.4K | 101.7K | 48.8% |

Consumer customers generate approximately **54% of total sales** and have the highest profitability among the three segments.

**Business implication:** Consumer is the strongest combination of scale and profitability, while Corporate has room for margin improvement.

---

### 📦 Product Category Performance

Sales are distributed across three major categories:

| Category | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Furniture | 568.6K | 275.0K | 48.4% |
| Office Supplies | 421.6K | 212.7K | 50.4% |
| Technology | 277.4K | 139.3K | 50.2% |

Furniture generates the highest sales, while **Office Supplies and Technology have slightly stronger profit margins**.

---

### 🏆 Sub-Category Performance

Several sub-categories stand out based on sales and profitability.

**Highest sales:**

1. Bookcases — **273.7K**
2. Chairs — **171.3K**
3. Appliances — **157.4K**
4. Copiers — **90.9K**
5. Storage — **85.6K**

**Highest profit margins:**

1. Machines — **55.6%**
2. Tables — **54.8%**
3. Envelopes — **53.2%**
4. Storage — **53.0%**
5. Labels — **53.0%**

This shows that the highest-revenue products are not necessarily the highest-margin products.

**Business implication:** High-margin sub-categories such as Machines, Tables, and Storage may offer opportunities for improving the overall product mix.

---

### 🚚 Shipping Mode Analysis

Economy shipping accounts for the largest share of orders:

| Ship Mode | Orders | Sales | Profit Margin |
|---|---:|---:|---:|
| Economy | 2,443 | 749.4K | 48.9% |
| Economy Plus | 838 | 274.2K | 52.0% |
| Priority | 617 | 174.1K | 49.1% |
| Immediate | 217 | 69.9K | 46.4% |

**Economy Plus has the highest profit margin at approximately 52.0%**, while Immediate has the lowest at approximately 46.4%.

---

### 📈 Order Trend

Order volume increased over the four-year period:

| Year | Orders | Sales | Profit |
|---|---:|---:|---:|
| 2017 | 753 | 229.4K | 111.5K |
| 2018 | 944 | 289.6K | 153.3K |
| 2019 | 1,093 | 344.9K | 173.2K |
| 2020 | 1,325 | 403.7K | 189.0K |

Orders increased from **753 in 2017 to 1,325 in 2020**, representing approximately **76% growth**.

Sales also increased from **229.4K to 403.7K** over the same period.

However, profit margin declined from approximately **48.6% in 2017 to 46.8% in 2020**.

**Business implication:** The business is growing in volume and revenue, but the decline in margin suggests that profitability should be monitored as sales scale.

---

## 🗺️ Geographic Analysis

The dashboard includes a geographic view of sales across the countries covered in the dataset.

The largest markets by sales are:

| Country | Sales | Profit |
|---|---:|---:|
| France | 348.3K | 167.8K |
| United Kingdom | 236.8K | 114.0K |
| Germany | 236.4K | 120.4K |
| Spain | 140.4K | 69.8K |
| Italy | 130.6K | 68.0K |

**France is the largest country-level market**, contributing approximately 27.5% of total sales.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Git / GitHub**

---

## 🔄 Data Analysis Workflow

```text
Raw Excel Dataset
        ↓
Data Cleaning & Transformation
        ↓
Power Query
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Power BI Visualizations
        ↓
Business Insights
