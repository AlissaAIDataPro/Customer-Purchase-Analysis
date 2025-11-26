# Customer-Purchase-Analysis
End-to-end Power BI dashboard showcasing customer behavior, subscription impact, and revenue drivers for a fashion retailer – data pipeline built with SQL and Python (Pandas, data cleaning &amp; feature engineering) before visualization and storytelling in Power BI.

# Customer Behavior & Revenue Insights Dashboard  
**Fashion Retail Analytics | End-to-End Data Project**

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=white)](https://powerbi.microsoft.com/) 
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) 
[![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)](https://www.postgresql.org/) 
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

### Live Dashboard (Published to Power BI Service)  
🔗 [View Interactive Report](https://github.com/AlissaAIDataPro/Customer-Purchase-Analysis/blob/main/Customer%20Purchase%20Behavior%20%26%20Revenue%20Insights%20Dashboard%20Report.pdf)

### Project Overview
An executive-ready Power BI dashboard that uncovers customer purchasing patterns, subscription impact, and top-performing product categories for a mid-size fashion retailer (3.9K customers).  
Built from raw data to final stakeholder presentation — 100% end-to-end.

### Dataset
- Source: Synthetic retail dataset (~4K customer records)  
- Key tables: Customers, Orders, Products, Reviews  
- Fields include gender, age group, subscription status, purchase amount, category, review rating, etc.

### Tools & Technologies Used
| Category              | Tools Used                                  |
|-----------------------|---------------------------------------------|
| Data Ingestion        | Python (Pandas)                             |
| EDA & Cleaning        | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database              | PostgreSQL (also tested on MySQL & SQL Server) |
| Querying              | SQL (JOINs, CTEs, window functions)         |
| Visualization         | Power BI (DAX measures, custom theme, bookmarks, drill-through) |
| Presentation          | Gamma.app (modern slide deck)               |

### Project Steps
1. **Data Loading & EDA**  
   Loaded raw CSV files in Python → explored distributions, missing values, and outliers using Pandas and Seaborn.

2. **Data Cleaning & Feature Engineering**  
   Handled duplicates, fixed data types, created age groups, calculated customer lifetime value, and flagged high-value customers.

3. **SQL Data Pipeline**  
   Created schema and tables in PostgreSQL → loaded cleaned data → wrote complex SQL queries (aggregations, cohort analysis, running totals).

4. **Power BI Dashboard Development**  
   Connected directly to PostgreSQL → built 3-page interactive report with KPIs, modern donut charts, insight cards, bookmarks, and drill-through.

5. **Storytelling & Presentation**  
   Exported key insights → created a clean, animated stakeholder presentation using Gamma.app.

### Dashboard Highlights
- Executive summary with total revenue, AOV, and subscription rate (27%)  
- Revenue & sales contribution by product category (Clothing = 52% of revenue)  
- Customer segmentation by age, gender, and subscription status  
- Actionable insights with on-screen text boxes  
- Mobile-optimized (16:9 layout)

### Key Results & Business Insights
- Only 27% of customers are subscribed → clear growth opportunity  
- Clothing drives over half of revenue but has lower ratings → quality focus needed  
- Accessories have the highest average transaction value → perfect for cross-sell campaigns  
- Young adults give highest ratings but spend less → acquisition vs monetization trade-off

### How to Run Locally
```bash
# 1. Clone repo
git clone https://github.com/yourusername/retail-customer-analytics.git

# 2. Install Python requirements
pip install -r requirements.txt

# 3. Run data cleaning script
python scripts/clean_and_load.py

# 4. Start PostgreSQL and run schema + data load SQL scripts
# 5. Open Retail_Customer_Dashboard.pbix in Power BI Desktop
```

### Repository Files
| File                                                                 | Description                                           |
|--------------------------------------------------------------------|-------------------------------------------------------|
| `customer_shopping_behavior.csv`                                   | Raw source dataset                                    |
| `Customer Behavior & Revenue Insights - Retail Analytics Dashboard.pbix` | Complete Power BI file (open in Power BI Desktop)     |
| `Customer Purchase Behavior & Revenue Insights Dashboard Report.pdf`     | Static PDF export of the full dashboard               |
| `Customer-Purchase-Behavior-and-Revenue-Insights.pptx`            | Stakeholder presentation deck (PowerPoint)            |
| `README.md`                                                        | This file                                             |

### Connect with Me
🔗 [LinkedIn](https://www.linkedin.com/in/alissakhan-data/) | Open to freelance & full-time Data Analyst / Data Engineer roles

Made with ☕ and clean DAX in 2025. 
