# 🎵 Music Store Sales Analytics – SQL Server & Power BI Project

## 📌 Project Overview
This project analyzes sales data from a digital music store using the Chinook database, SQL Server, and Power BI to uncover key business insights and support data-driven decision-making.

---

## 🎯 Project Goals
- Analyze total store revenue  
- Identify top spending customers  
- Discover best-performing music genres  
- Track revenue trends over time  
- Evaluate top artists by revenue  

---

## 🛠️ Tools & Technologies
- SQL Server (SSMS)  
- SQL Server Express  
- Power BI Desktop  
- DAX  
- Chinook Database  

---

## 🗄️ Database Structure
**Tables Used:**
- Artist  
- Album  
- Track  
- Genre  
- Customer  
- Invoice  
- InvoiceLine  

**Relationship Flow:**  
Artist → Album → Track → InvoiceLine → Invoice → Customer  

---

## 📊 SQL Analysis
- Total Revenue  
- Revenue by Country  
- Top Customers  
- Revenue by Genre  
- Top Artists  

---

## 🧩 SQL Views
- RevenueByCountry  
- GenreRevenue  
- TopCustomers  

---

## ⭐ Stored Procedure
`GetTopCustomers` – returns top 10 customers by spending  

---

## 📈 Power BI Dashboard

### Overview
- Revenue KPI  
- Tracks Sold  
- Avg Unit Price  
- Total Customers  
- Revenue Trend  
- Revenue by Country  

### Customer Insights
- Top 10 customers  
- Spending analysis  
- Country filter  

### Genre Insights
- Revenue by genre  
- Top-performing genres  

---

## 📐 DAX Measures
```DAX
Total Revenue = SUM(Invoice[Total])
Tracks Sold = SUM(InvoiceLine[Quantity])
Avg Unit Price = AVERAGE(InvoiceLine[UnitPrice])
Total Customers = DISTINCTCOUNT(Customer[CustomerId])

##
--- 
 ## 🔍 Key Insights
- 💰 Total revenue reached **$2.33K**, showing overall business performance  
- 📈 Revenue grew by **13.5%**, indicating positive sales trends  
- 🌍 **USA** generated the highest revenue, making it the top market  
- 🎸 **Rock** was the best-performing genre by revenue contribution  
- 👤 **Helena Holý** was the highest-spending customer  

---

## 🔗 Connect With Me
- LinkedIn: https://www.linkedin.com/in/keren-oyem  
- GitHub: https://github.com/kerenoyem-hash
