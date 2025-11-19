# 📊 Sales Segmentation – RFM Analysis (Power BI Dashboard)

This repository showcases an advanced **RFM (Recency, Frequency, Monetary) Analytics Dashboard** built in **Power BI** to segment customers, analyze sales patterns, and provide decision-ready insights for business users.

The dashboard analyzes customer behavior using RFM segmentation and helps identify key customer groups such as **Champions, Loyal Customers, Big Spenders, At Risk, Lost**, and more.

![RFM Analysis_PowerBI](<images/RFM Analysis_PowerBI.png>)

---

## 📊 Business Problem

Sales and marketing teams often:
- Don’t know **which customers are most valuable**
- Struggle to **prioritize retention vs. acquisition**
- Lack an easy way to track **recency, frequency and spend** in one view

This dashboard solves that by:
- Classifying customers with **RFM scoring**
- Showing **segment distribution**
- Highlighting **monthly sales trends** and **category-wise performance**
- Providing a detailed **customer-level drill-down**

---

# 📁 Project Structure

```bash
powerbi-sales-rfm-dashboard/
│
├── RFM Analysis_Sales_PowerBI.pbix # Main Power BI dashboard
│
├── data/
│ └── Superstore 2025.csv # Source dataset used in the model
│
├── images/
│ └── RFM Analysis_PowerBI.png # Dashboard preview image
│
├── docs/
│ └── DAX.pdf # Complete DAX documentation (measures, tables, scoring)
│
└── README.md # Project documentation

```
---

# 📌 Overview

The **Sales RFM Analysis Dashboard** helps businesses:

- Identify high-value customers  
- Track customer recency & buying frequency  
- Understand revenue contribution through RFM metrics  
- Segment customers into meaningful behavioral groups  
- Monitor monthly sales trends & customer activity  
- Improve retention & marketing strategy based on data  

---

# 🎯 Key Features

### **1. KPI Summary**
- Total Sales  
- Average Recency  
- Average Frequency  
- Average Monetary Value  
- YoY Variations with up/down icons  
- Dynamic color indicators (green/red/orange)

### **2. Monthly Trend Analysis**
- Combination chart of monthly Sales & Customer Count  
- Tooltips with monthly details  
- Supports filtering by City & Year

### **3. Customer Segmentation**
- RFM Segment Split (Champions, Loyal, At-Risk, Lost, etc.)  
- Bar chart distribution of customers by segment  

### **4. Category Split**
- Customer distribution by product categories (Office Supplies, Furniture, Tech)

### **5. Customer-Level Drilldown**
- Customer ID
- Segment classification  
- Recency, Frequency, Monetary values  
- Horizontal bars for visual comparison  

### **6. Interactive Slicers**
- City  
- Year  

---

# 🧮 RFM Methodology

**RFM Scoring Logic:**

| Metric    | Meaning |
|-----------|---------|
| Recency   | Days since last purchase |
| Frequency | Number of orders placed |
| Monetary  | Total spending |

Customers receive a score from **1 to 5** (1 = best, 5 = worst).  
These are combined into segments such as:

- **Champions**
- **Loyal Customers**
- **Big Spenders**
- **At Risk**
- **Lost**
- Others

Full DAX logic is included in:  
[📘 ALL USED DAX](docs/DAX.pdf)

---

# 🛠 Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **CSV Dataset**
- **Data Modeling + Calculated Tables**
- **RFM Segmentation Logic**

---

# 🚀 How to Use

1. Clone or download the repository:
    ```bash
    git clone https://github.com/<your-username>/powerbi-sales-rfm-dashboard.git
    ```
2. Open the `.pbix` file in Power BI Desktop.
3. Ensure the file path for `Superstore 2025.csv` matches your local machine.
4. Refresh data and explore interactive visuals.



---

# 📚 Documentation

Complete DAX logic used in the report is available here:  
[📘 ALL USED DAX](docs/DAX.pdf)

Includes:
- KPI Measures  
- YoY Variance Measures  
- RFM Scoring  
- RFM Segment Logic  
- Date Table  
- RFM Summary Table  

---

# 👤 Author – Jaymin Patel

**Business & Data Analyst | Power BI | SQL | Python**

📌 **LinkedIn:** https://www.linkedin.com/in/jaymin7/  
📌 **GitHub:** https://github.com/jayminmech7  
📌 **Portfolio Website:** https://jayminmech7.github.io/  

---


