# ☕ Coffee Shop Sales Analysis | Excel Dashboard

##  Project Overview
Performed end-to-end sales analysis for a coffee shop chain using **Microsoft Excel & Power Query**.
**Goal:** Convert raw sales data into actionable business insights through an interactive dashboard.

##  Tools & Technologies
- **Microsoft Excel**: Dashboard, Pivot Tables, Slicers, Charts
- **Power Query**: ETL, Data Cleaning & Transformation
- **DAX**: Calculated Measures

##  Data Cleaning & Transformation using Power Query

1. **Date Standardization**: Converted text date column to proper Date format
2. **Text Cleaning**: Used `Trim` & `Clean` functions to remove extra spaces and unwanted characters
3. **Feature Engineering**: 
   - **Custom Column**: Created `Size` column based on product type
   - **Conditional Column**: Categorized orders based on bill amount
   - **Extracted from Time**: `Hour`, `Day Name of Week`, `Month Name` for trend analysis
4. **Data Type Fixes**: Corrected data types for Price, Quantity, and Date columns
5. **Removed Duplicates & Nulls**: Ensured data quality for accurate reporting

##  Key Insights from Dashboard

| Metric | Value | Insight |
| **Total Revenue** | $6,986,812.33 | Sum of all order prices |
| **Total Footfall** | 149,116 | High customer traffic |
| **Avg Bill/Person** | $4.69 | Pricing strategy working |
| **Avg Order Value** | $4.44 | Consistent basket size |

**Dashboard Visualizations:**
1. **Hourly Orders Trend**: Peak sales between 8-10 AM. Morning coffee rush ☕
2. **Category % by Sales**: Coffee beans & Espresso are top revenue drivers
3. **Size Distribution**: Medium & Large sizes dominate 70%+ orders
4. **Store Performance**: Hell's Kitchen leads in both footfall & sales
5. **Top 5 Products**: Barista Espresso, Brewed Black Tea are bestsellers
6. **Monthly Trends**: Interactive slicers for Month & Day analysis


