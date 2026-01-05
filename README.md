# Financial_Dashboard_Report

# 📊 Financial Dashboard Report (Power BI)

Project Overview

This project presents a comprehensive Financial Performance Dashboard developed using Power BI. The objective of the dashboard is to provide a clear and structured view of a company’s financial health by analyzing revenue trends, profitability metrics, cash flow movement, receivables aging, and budget performance.

The dashboard is designed as a single-page executive report that combines key performance indicators (KPIs), analytical visuals, and interactive slicers to enable dynamic exploration of financial data across different products, regions, and time periods.

Dashboard Components

1. Key Performance Indicators (KPIs)

The dashboard highlights the following core financial KPIs at the top level:

🔹Total Revenue: Represents the overall revenue generated during the selected period

🔹Gross Margin Percentage: Indicates operational efficiency by comparing gross profit against revenue

🔹EBITDA Percentage: Measures operating profitability before interest, tax, depreciation, and amortization

🔹Net Cash Position: Shows the net liquidity position derived from cash inflows and outflows
These KPIs provide a quick summary of financial performance and are dynamically updated based on slicer selections.

2. Analytical Visualizations

The dashboard includes the following visuals to support detailed financial analysis:

🔹Revenue and Profit 
Trend Displays monthly trends for total revenue and gross profit, helping identify growth patterns and seasonal variations.

🔹Budget vs Actual Variance Analysis
Compares actual revenue against budgeted revenue on a monthly basis to assess budget accuracy and financial planning effectiveness.

🔹Product / Service Performance
Analyzes revenue contribution by product or service category to identify top-performing and underperforming offerings.

🔹Receivables Aging Analysis
Segments outstanding receivables into aging buckets (0–30 days and 31–60 days) to monitor collection efficiency and credit risk.

🔹Monthly Net Cash Flow Trend
Illustrates month-wise net cash movement, clearly highlighting periods of positive and negative cash flow.

3. Interactive Filtering (Slicers)

The dashboard supports dynamic analysis through the following slicers:

Product / Service
Region
Month (with year and quarter hierarchy)
These slicers allow users to drill down into specific segments and analyze financial performance from multiple perspectives.

DAX Logic and Calculations
The following key calculations were implemented using DAX:

🔹Variance Percentage
(Actual Revenue – Budget Revenue) ÷ Budget Revenue

🔹Net Cash Flow
Total Cash Inflows – Total Cash Outflows

🔹EBITDA Percentage
EBITDA ÷ Total Revenue

🔹Receivables Aging Buckets
Custom groupings created using calculated columns to categorize receivables by aging period

🔹Cash Flow Calculations
Conditional logic applied to correctly represent inflows, outflows, and net cash movement in visuals

Key Insights

🔹Revenue shows a generally stable trend with consistent gross profit margins across months

🔹Net cash flow remains positive in most periods, indicating healthy liquidity management

🔹Budget variance analysis highlights months with deviations, supporting improved financial forecasting

🔹Certain products and services contribute disproportionately to total revenue

🔹Majority of receivables fall within the 31–60 day range, indicating moderate collection cycles

Project Structure

Power BI Dashboard

🔹Data Model and Relationships

🔹DAX Measures and Calculated Columns

🔹Interactive Visualizations

🔹Final Executive Report Layout

Tools and Technologies Used

🔹Power BI

🔹Microsoft Excel

🔹DAX

🔹Power Query

Conclusion

🔹This project demonstrates an end-to-end financial reporting solution using Power BI, covering data modeling, financial calculations, and professional dashboard design. The dashboard is structured to support both high-level executive decision-making and detailed financial analysis through interactive visuals and filters.

🔹Created by: Devang


