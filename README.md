# Personal Finance Dashboard

This project demonstrates how to create a comprehensive **Personal Finance Dashboard** using **Power BI** and **DAX queries**. The dashboard provides an interactive view of your financial data, including expenses, savings, and investments, enhanced with **Tooltips** for detailed insights.

## Features
- 📊 Visualize income, expenses, savings, and investments.
- 🧮 Dynamic insights powered by **DAX queries**.
- 🛠️ Interactive **Tooltips** for in-depth exploration of data points.
- 📈 Customizable visuals to suit your financial tracking needs.

## Requirements
- **Power BI Desktop**
- Basic knowledge of Power BI and DAX
- Sample financial dataset (CSV/Excel format)

## Steps to Create the Dashboard

### 1. Prepare Your Data
- Collect your financial data (income, expenses, savings, etc.) in a structured format.
- Import the dataset into Power BI.

### 2. Design the Dashboard Layout
- Sketch a layout for key sections: 
  - Monthly Income and Expense Overview
  - Savings Trend
  - Investment Breakdown
- Arrange visuals (e.g., bar charts, line charts, pie charts) accordingly.

### 3. Create DAX Measures
Use DAX queries to generate calculated fields:
```DAX
TotalIncome = SUM(FinancialData[Income])
TotalExpenses = SUM(FinancialData[Expenses])
NetSavings = [TotalIncome] - [TotalExpenses]
SavingsPercentage = DIVIDE([NetSavings], [TotalIncome], 0) * 100
```

### 4. Add Interactive Tooltips
- Enable **Tooltips** in visuals to display detailed insights.
- Customize tooltips for key metrics like:
  - Expense categories
  - Savings breakdown by month

### 5. Customize and Publish
- Apply themes and formatting for a professional look.
- Test interactivity and responsiveness.
- Publish your dashboard to Power BI Service for sharing.

## Usage
1. Open the Power BI file.
2. Connect to your data source.
3. Update visuals and tooltips as needed.

## Future Improvements
- Incorporate predictive analytics for savings growth.
- Add budget vs. actual comparison charts.

### Let's make tracking finances easier and smarter! 🚀
