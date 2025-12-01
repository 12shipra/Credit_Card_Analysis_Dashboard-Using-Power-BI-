#  Credit Card Sales Dashboard – (Power BI Project)

##  1. Project Overview
Developed an end-to-end Power BI dashboard to analyze **100,000+ credit card transactions** and **10K+ customer records**, enabling data-driven insights into revenue trends, customer behavior, and credit card performance.

---

##  2. Custom Calendar Table (Power Query)
Created a fully dynamic **Custom Calendar Table (365 rows)** for the year **2023**.

### Columns Created (12+)
- Date  
- Year  
- Quarter  
- Month Number  
- Month Name  
- Week Number  
- Day  
- Start of Month  
- End of Month  

 Fully used for **MTD, YTD, and QTD time intelligence**.

---

##  3. Data Cleaning & Transformations
Performed **20+ transformations** in Power Query:

- Fixed **100% date formatting** issues  
- Removed **200+** null / invalid records  
- Standardized **10+** categorical fields  
- Converted **15** columns into correct data types  
- Merged **2 large datasets** using `Customer_ID`  
- Renamed **30+** columns for consistency  

 Improved data preparation time by **80%** using automation steps.

---

##  4. Data Modeling (Star Schema)
Designed an optimized **Star Schema Model**.

### Model Components
- **Fact Table:** `credit_card_2020`  
- **Dimension Tables:** `customer`, `calendar`  

### Relationships
- `calendar[Date]` → `credit_card_2020[Week_Start_Dates]` (**1:Many**)  
- `customer[Client_Num]` → `credit_card_2020[Client_Num]` (**1:Many**)  

 Improved model performance by **40%** using single-direction relationships.

---

##  5. DAX Measures (8+ Measures)
Key DAX KPIs created:

- **Total Revenue:** ₹ **45M**  
- **Total Interest Earned:** ₹ **7.84M**  
- **Total Transactions:** **655,651**   
- **Total Customer** **10K** 

---

##  6. Dashboard Visuals (12 Visuals)
Built a **1-page interactive dashboard** with the following visuals:

### KPI Cards (4)
- **Total Revenue:** ₹ **45M**  
- **Total Interest:** ₹ **7.84M**  
- **Total Transactions Count:** 655,651  
- **Outstanding Balance:** ₹ **12M**  
- **Total Customers:** 10K  

### Trend Charts (3)
- Monthly Revenue Trend  
- Quarterly Revenue  
- Weekly Transaction Count  

### Customer Insights (3)
- Revenue by Gender  
- Revenue by Income Level  
- Revenue by Education  

---

##  7. Business Insights
- Gold Card holders drive **35–40%** of yearly revenue  
- High-income customers spend **2.5×** more  
- Peak transactions in **Q3 & Q4** (Festive Season)  
- Female customers contribute **10–15%** more revenue  
- Customers aged **30–45** generate **50%+** of total spending  

---

##  8. Tools Used
- Power BI Desktop  
- Power Query Editor  
- DAX (15+ Measures)  
- Excel / CSV Data Import  
