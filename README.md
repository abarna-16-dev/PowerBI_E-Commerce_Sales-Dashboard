# PowerBI_E-Commerce_Sales-Dashboard
Interactive E-Commerce Sales Dashboard built in Power BI | Analyzed 6M+ Sales, Profit &amp; Margin Trends | DAX, KPI Cards, Maps &amp; Slicers | Data Analyst Portfolio Project
# 🛒 E-Commerce Sales Dashboard - Power BI

This dashboard provides a comprehensive analysis of E-Commerce sales performance, profitability, and customer trends.

### 📊 Key KPIs
- **Total Sales:** 6M
- **Total Profit:** 856K
- **Profit Margin %:** 14.2%
- **Total Orders:** 13K
- **Total Quantity Sold:** 2M

### 📈 Visuals Included
1. **KPI Cards:** Sales, Profit, Margin, Orders
2. **Sales by Category & Payment Mode:** Donut / Bar Chart
3. **Sales by State:** Filled Map / Bar Chart
4. **Monthly Sales Trend:** Line Chart with Target
5. **Slicers:** Category, State, Payment Mode, Year-Month

### 🛠️ DAX Measures Used
```DAX
Total Sales = SUM('E-Commerce Sales'[Amount])
Total Profit = SUM('E-Commerce Sales'[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
Total Orders = COUNT('E-Commerce Sales'[Order ID])
