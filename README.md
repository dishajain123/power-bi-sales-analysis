# Power BI Sales Data Analysis Dashboard

A comprehensive sales analytics dashboard built with Power BI to provide actionable business insights through interactive visualizations and data analysis.

## Overview

This project transforms raw sales data into meaningful business intelligence through interactive dashboards. The solution analyzes sales performance across customers, products, promotions, and time periods to support data-driven decision making.

## Features

### 📊 Dashboard Pages

**Product Performance Analysis**
- Top/Bottom 5 products by sales, units sold, and profit
- Performance comparison charts
- Product profitability analysis

**Sales Overview Dashboard**
- Sales trend analysis with time-based filtering
- Profit vs sales correlation analysis
- Promotional effectiveness metrics
- Geographic sales distribution map
- Order volume tracking

**Comparative Analysis**
- Period-to-period comparison
- Interactive date range selection
- Detailed transaction views
- Multi-dimensional filtering

### 🔧 Key Features
- Interactive charts with drill-down capabilities
- Dynamic filtering and slicing
- Real-time data updates
- Cross-visual highlighting
- Mobile-responsive design

## Data Structure

**Star Schema Design**
- **Fact Table**: Sales transactions and metrics
- **Dim Customer**: Customer demographics and information
- **Dim Product**: Product catalog and details
- **Dim Promotion**: Promotional campaigns and discounts

**Key Metrics**
- Net Sales (after discounts)
- Total Sales (gross revenue)
- Profit (calculated margins)
- Units Sold
- Discount Amount
- Order Count

## Prerequisites

- Microsoft Power BI Desktop
- Excel workbook with sales data (4 tables)
- Basic understanding of Power BI interface

## Quick Start

1. **Download and Install**
   - Install Power BI Desktop from Microsoft
   - Prepare your Excel data file with the required tables

2. **Import Data**
   ```
   Get Data → Excel Workbook → Select all 4 tables → Load
   ```

3. **Data Preparation**
   - Clean and validate data quality
   - Create calculated columns for metrics
   - Establish table relationships

4. **Build Dashboard**
   - Create visualizations as per requirements
   - Apply formatting and styling
   - Configure interactive filters

## Data Transformations

**Calculated Columns Created:**
- `Total Sales = Unit Sales × Price per Unit`
- `Discount Amount = Total Sales × Discount Percentage ÷ 100`
- `Net Sales = Total Sales - Discount Amount`
- `Profit = Net Sales × 0.1`
- `Order Index = Sequential numbering`

## Business Value

**Insights Delivered:**
- Product performance identification
- Sales trend analysis
- Customer behavior patterns
- Promotional effectiveness measurement
- Geographic performance analysis
- Profitability optimization opportunities

**Decision Support:**
- Inventory management optimization
- Data-driven marketing strategies
- Resource allocation guidance
- Pricing strategy development
- Market expansion planning

## Usage

1. Open the `.pbix` file in Power BI Desktop
2. Refresh data connections if needed
3. Navigate between dashboard pages using tabs
4. Use slicers and filters for interactive analysis
5. Export reports or publish to Power BI Service

## Technical Details

**Performance Optimizations:**
- Star schema data model
- Proper data types and relationships
- Efficient calculated columns
- Optimized visual interactions

**Visualization Types:**
- Bar charts for comparisons
- Line charts for trends
- Scatter plots for correlations
- Maps for geographic analysis
- Cards for key metrics
- Tables for detailed views

---

*Built with Microsoft Power BI Desktop*
