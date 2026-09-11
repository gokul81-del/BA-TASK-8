# Business Category Analysis using Tree Map in Tableau

## 1. Project Title

**Business Category Analysis using Tree Map in Tableau**

---

## 2. Objective

The objective of this project is to analyze the contribution of different business categories using Tableau Tree Map visualization and identify the categories that have the greatest impact on business performance.

The project uses sales-related data to compare product lines, deal sizes, countries, and yearly sales performance.

---

## 3. Dataset

**Dataset Name:** Sales Data Sample

**File Name:** `Sales_Data_Sample(1).csv`

**Source:** Kaggle

The dataset contains business sales information including product categories, sales amount, order quantity, countries, deal sizes, order status, and order dates.

---

## 4. Tools Used

* **Tableau Public** – Data visualization and dashboard creation
* **CSV Dataset** – Data source
* **Kaggle** – Dataset source

---

## 5. Important Dataset Fields

| Field           | Description        |
| --------------- | ------------------ |
| PRODUCTLINE     | Product category   |
| DEALSIZE        | Order/deal size    |
| SALES           | Total sales amount |
| QUANTITYORDERED | Quantity ordered   |
| PRICEEACH       | Price per item     |
| COUNTRY         | Customer country   |
| YEAR_ID         | Order year         |
| STATUS          | Order status       |
| ORDERDATE       | Order date         |

---

## 6. Tree Map Analysis

A Tree Map was created to analyze sales contribution across different product lines and deal sizes.

### Tree Map Configuration

* **Size:** SUM(SALES)
* **Color:** SUM(SALES)
* **Category:** PRODUCTLINE
* **Sub-category:** DEALSIZE

The size of each block represents the sales contribution of the category. Larger blocks indicate higher sales.

---

## 7. Additional Visualizations

Three additional visualizations were created along with the Tree Map.

### 7.1 Sales by Product Line

A horizontal bar chart was created to compare sales across different product lines.

**Chart Type:** Bar Chart

**Dimension:** PRODUCTLINE

**Measure:** SUM(SALES)

---

### 7.2 Year-wise Sales Trend

A line chart was created to analyze how sales changed over different years.

**Chart Type:** Line Chart

**Dimension:** YEAR_ID / ORDERDATE

**Measure:** SUM(SALES)

---

### 7.3 Sales by Country

A Filled Map was created to compare sales performance across different countries.

**Chart Type:** Filled Map

**Geographical Field:** COUNTRY

**Measure:** SUM(SALES)

---

## 8. Dashboard

All four visualizations were combined into a single interactive dashboard named:

**Business Sales Performance Dashboard**

The dashboard contains:

1. Sales Contribution Tree Map
2. Sales by Product Line Bar Chart
3. Year-wise Sales Trend Line Chart
4. Sales by Country Filled Map

---

## 9. Dashboard Filters

The following filters were added to make the dashboard interactive:

* YEAR_ID
* PRODUCTLINE
* DEALSIZE

The filters can be applied across worksheets using the same data source.

This allows users to explore sales performance for specific years, product categories, and deal sizes.

---

## 10. Business Insights

### Insight 1

The Tree Map shows that sales contribution is not evenly distributed across all product lines. Some product categories contribute significantly more to total sales.

### Insight 2

Different deal sizes contribute differently to overall sales. High-value deals can have a considerable impact on total business revenue.

### Insight 3

Sales performance varies across countries. Some geographical markets contribute significantly more sales than others.

### Insight 4

The yearly sales trend shows changes in business performance over time and helps identify periods of higher and lower sales.

### Insight 5

The dashboard indicates that focusing on high-performing product categories and markets can help the business improve overall sales performance.

---

## 11. Business Recommendations

### Recommendation 1 — Focus on High-Performing Products

The company should prioritize high-performing product lines by maintaining sufficient inventory, improving marketing activities, and targeting customers interested in these products.

### Recommendation 2 — Improve Low-Performing Markets

Countries and product categories with lower sales should be analyzed further. Targeted promotions, localized marketing strategies, and improved customer engagement can be used to increase their sales contribution.

---

## 12. Conclusion

The Tableau dashboard provides an interactive view of business sales performance. The Tree Map makes it easy to identify the product categories contributing the most to sales, while the bar chart, line chart, and filled map provide additional information about product, time-based, and geographical performance.

The analysis can help businesses identify important revenue-generating categories, understand market performance, and make better data-driven decisions.

---

## 13. Project Structure

```text
Business Category Analysis
│
├── Sales_Data_Sample(1).csv
├── Tableau Workbook
│
├── Visualizations
│   ├── Sales Contribution Tree Map
│   ├── Sales by Product Line
│   ├── Year-wise Sales Trend
│   └── Sales by Country
│
└── Business Sales Performance Dashboard
```

---

## 14. Key Technologies

**Tableau Public | Data Visualization | Business Analytics | Tree Map | Dashboard | Sales Analysis**
(https://public.tableau.com/views/BUSINESSSALESPERFORMANCEDASHBOARD/BUSINESSSALESPERFORMANCEDASHBOARD?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
