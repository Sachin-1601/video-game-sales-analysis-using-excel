I’ll first inspect the contents of both datasets to understand their structure and identify potential project ideas. Let me check the first few rows and key statistics.

### **Excel Project: Video Game Sales Analysis**  

#### **Project Overview:**  
This project will analyze video game sales data to provide insights into game performance, popular genres, revenue distribution, and platform preferences.  

#### **Datasets Used:**  
1. **Games Dataset (`Games.csv`)**  
   - Contains details about video games, including **GameID, Title, Genre, Release Date, and Developer**.  
2. **Sales Dataset (`Game Sales.csv`)**  
   - Provides sales data by **GameID, Platform, Sales Region, Units Sold, and Price**.  

---

### **Project Tasks & Excel Skills Used**  

#### **1. Data Cleaning & Preparation** *(Power Query, Data Cleaning Functions)*  
- Convert `ReleaseDate` to **Date Format**.  
- Remove duplicates and correct inconsistencies in **Genre, Developer, and Platform** columns.  
- Merge both datasets using **VLOOKUP or Power Query (based on `GameID`)**.  

#### **2. Sales Performance Analysis** *(Pivot Tables, Charts, Formulas)*  
- **Total Revenue Calculation:** `UnitsSold * Price`.  
- **Top 10 Best-Selling Games:** Sort by total revenue.  
- **Genre Popularity:** Sum of total sales per genre.  
- **Platform Performance:** Total revenue per platform (Xbox, PlayStation, PC).  

#### **3. Regional Sales Insights** *(Pivot Tables, Conditional Formatting)*  
- **Compare sales across regions** (North America, South America, etc.).  
- Identify the **best-selling genre per region**.  
- **Heatmap visualization** of regional sales.  

#### **4. Release Year Trend Analysis** *(Date Functions, Line Charts)*  
- Group sales by **release year** and visualize trends.  
- Identify which year had the **highest total sales**.  

#### **5. Dashboard Creation** *(Power BI or Excel Dashboard Tools)*  
- **KPIs:**  
  - **Total Revenue, Best-Selling Game, Most Popular Genre, Top Region**.  
- **Visualizations:**  
  - Bar charts for **sales by platform**.  
  - Line chart for **yearly sales trends**.  
  - Pie chart for **sales by genre**.  

---

### **Project Outcome:**  
This project provides actionable insights into **game sales performance, platform preferences, and market trends**, helping game developers and marketers make **data-driven decisions**.  

Would you like an **Excel template** or step-by-step guide for implementation? 🚀
