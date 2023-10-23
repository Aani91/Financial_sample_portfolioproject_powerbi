# Financial_sample_portfolioproject_powerbi
Powerbi Project - Data Analysis of Financial Sample

## Introduction

Welcome to the Financial Sample Power BI report. This report provides insights into financial data, helping you analyze and visualize financial performance and trends. This document aims to guide you through the report's features and provide essential information for a better understanding.

### Report Overview

    Dashboard: The report consists of multiple dashboards, each focusing on different financial aspects. You can access these dashboards from the left-side navigation pane.

    Filters: To interact with the data, you can use filters located at the left and top of each dashboard. These filters allow you to customize the view based on your requirements.

    Visualizations: Visualizations such as charts, tables, and reports provide a comprehensive view of the financial data. You can click on elements within visualizations for more detailed information.

    Export: You can export specific data or visualizations using the "Export" option, allowing you to save or share the information in various formats.

### Dashboards
   #### Profit & Loss Analysis

    Offers a detailed analysis of revenues, expenses, and net profit over time.
    Helps identify trends and factors affecting financial performance.
    
   #### Product Analysis

    Analyzes product performance, including sales, profit, and quantity sold.
   Helps you understand which products contribute the most to revenue and profit.

   #### Geographic Analysis

     Offers geographic insights with maps and location-based data.
     Allows you to explore sales and customer distribution across country.
    

#### How to Use the Report

    Utilize filters to focus on specific time periods, departments, or financial metrics.
    Click on data points or visual elements to drill down for more detailed information.
    Explore different dashboards to obtain a well-rounded view of financial performance.

#### Measures Used

    The data in this report is based on the Financial Sample dataset and is periodically updated.
    Measure were created for the project.
    Gross Profit = SUM(financials[Gross Sales])-SUM(financials[COGS]) 
    Gross Profit Margin = DIVIDE([Gross Profit],[Net Sales]) %
    Net Profit = SUM(financials[ Sales])-SUM(financials[COGS])-SUM(financials[Discounts])
    Net Profit Margin = DIVIDE([Net Profit], [Revenue]) %
    Net Sales = SUM(financials[Gross Sales])-SUM(financials[Discounts])
    Profit per Unit Sold = SUM(financials[Profit]) / SUM(financials[ Sales])
    Revenue = SUM(financials[Gross Sales]) - SUM(financials[Discounts])
    Revenue per Unit Sold = SUM(financials[ Sales]) / SUM(financials[Manufacturing Price])

## Conclusion

We hope this Financial Sample Power BI report helps you gain a deep understanding of financial performance and aids in making informed financial decisions. 
Some insights from the analysis are:
1. France is the top profit making country.
2. Government segment has more sales and more profit.
3. Paseo is the top selling product.
4. VTT is the expensive product.
5. The gross profit is 26.10M.

If you have any questions or require further assistance, please do not hesitate to reach out to the report administrator. Enjoy your data analysis and exploration!
