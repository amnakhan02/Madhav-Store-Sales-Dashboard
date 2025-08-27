# 📊 Madhav Store Sales Dashboard – Power BI Project  

## 📌 Project Overview  
This project is an **interactive Power BI dashboard** designed to analyze and visualize **Madhav Store sales performance** across states, categories, and time periods.  
The dashboard turns raw sales data into **actionable insights** with the help of slicers, KPIs, and drill-down visuals.  

## ✨ Features  
✅ Interactive **slicers** for State, Quarter, Category, and Customer  
✅ **KPIs** for Sales, Profit, and Quantity  
✅ **Drill-down** visuals for state-wise and category-wise analysis  
✅ Payment Mode analysis (**COD vs Cards**)  
✅ **Month-wise trends** to identify peak sales periods  
✅ Highlights **profitable vs loss-making products**  

## 📊 Key Insights  
- **Delhi**: ~2.2k sales, ~557 profit | Clothing dominates with 60% | Bookcases = strong profit driver | COD > Cards  
- **Sikkim**: ~1.6k sales, ~39 profit | Phones = most profitable | Trousers & Tables = losses | Clothing (47%), Electronics (40%)  
- **Delhi > Sikkim** in profitability  
- **April = peak month** for both states  
- **Maharashtra** leads sales (~15k)  
- **Phones** are the most demanded category  

## 🛠 Tools & Techniques  
- 📌 **Power BI** – Data visualization, DAX measures  
- 📌 **Excel** – Data cleaning  
- 📌 **DAX** – Calculated measures, KPIs  

## 🔄 Data Preparation (ETL Workflow)  
The dataset was **cleaned and transformed** before building the dashboard. Steps included:  

### 1️⃣ Extract  
- Raw data collected from Madhav Store’s sales records (CSV format).  
- Imported into **Excel** and **SQL** for cleaning and preprocessing.  

### 2️⃣ Transform  
- **Removed missing/null values** in sales and profit columns.  
- **Standardized date format** (YYYY-MM-DD) for consistency.  
- Created a **derived column** for Month & Quarter.  
- Categorized **Product Categories** into higher-level groups (Clothing, Electronics, Furniture).  
- **Calculated fields**: Profit Margin %, Sales Contribution %.  

### 3️⃣ Load  
- Cleaned dataset loaded into **Power BI Desktop**.  
- Data Model created with **relationships** between Fact (Sales) and Dimension tables (State, Category, Customer).  
- DAX measures added for **Sales, Profit, Quantity, Profit %**.  


