# Power BI Sales Data Analysis Project

A comprehensive sales data analysis dashboard built with Power BI, featuring interactive visualizations and advanced data transformations to provide business insights.

## 📊 Project Overview

This Power BI project analyzes sales data across multiple dimensions including customers, products, promotions, and time periods. The dashboard provides actionable insights through interactive charts, KPI cards, and filtering capabilities.

## 🗂️ Data Structure

The project uses a **Star Schema** design with the following tables:

### Dimension Tables
- **Dim Customer**: Customer information and demographics
- **Dim Product**: Product catalog and details  
- **Dim Promotion**: Promotional campaigns and discount information

### Fact Table
- **Fact Table**: Transactional data with sales metrics

## 🚀 Features

### Dashboard Pages

#### Page 1: Product Performance Analysis
- **Top 5 Products by Sales**: Bar chart showing highest performing products
- **Bottom 5 Products by Sales**: Identifying underperforming products
- **Top 5 Products by Units Sold**: Volume-based performance metrics
- **Bottom 5 Products by Units Sold**: Low-volume product analysis
- **Top 5 Products by Profit**: Most profitable product identification
- **Bottom 5 Products by Profit**: Least profitable product analysis

#### Page 2: Sales Overview Dashboard
- **Sales Trend Analysis**: Line chart showing sales performance over time with drill-down capabilities
- **Profit vs Net Sales Correlation**: Scatter plot analyzing relationship between profit and sales
- **Average Discount by Promotion**: Bar chart showing promotional effectiveness
- **Geographic Sales Distribution**: Map visualization showing sales by city/state
- **Total Orders Counter**: Card visualization displaying order volume

#### Page 3: Comparative Analysis
- **Period Comparison**: Side-by-side analysis of sales, profit, and quantity metrics
- **Interactive Date Filters**: Dual date slicers for period comparison
- **Detailed Transaction Table**: Comprehensive order-level data view
- **Multi-dimensional Filtering**: Customer, product, and promotion filters

## 🛠️ Data Transformation Process

### Data Loading
1. Import Excel workbook with multiple sheets
2. Load 4 tables: Dim Customer, Dim Product, Dim Promotion, and Fact Table

### Data Cleaning & Preparation
- **Column Quality Assessment**: Identify and handle null/error values
- **Data Type Optimization**: Ensure correct data types for all columns
- **Primary Key Validation**: Verify uniqueness of key columns

### Calculated Columns Created
- **Total Sales**: `Unit Sales × Price per Unit`
- **Discount Amount**: `Total Sales × Discount Percentage ÷ 100`
- **Net Sales**: `Total Sales - Discount Amount`
- **Profit**: `Net Sales × 0.1` (10% profit margin assumption)
- **Order Index**: Sequential numbering for order tracking

### Data Model Relationships
- Established proper relationships between dimension and fact tables
- Implemented referential integrity with primary/foreign key constraints
- Created star schema for optimal performance

## 📈 Key Metrics & KPIs

- **Net Sales**: Revenue after discounts
- **Total Sales**: Gross revenue before discounts
- **Profit**: Calculated profit margins
- **Units Sold**: Product volume metrics
- **Discount Amount**: Total promotional savings
- **Order Count**: Transaction volume

## 🎛️ Interactive Features

### Filtering Capabilities
- **Visual-level Filters**: Chart-specific filtering
- **Page-level Filters**: Entire page filtering
- **Report-level Filters**: Cross-page filtering
- **Date Range Selection**: Period-based analysis
- **Multi-select Slicers**: Customer, product, and promotion filtering

### Visual Interactions
- **Drill-down/Drill-up**: Time-based navigation
- **Cross-filtering**: Interactive chart relationships
- **Hover Tooltips**: Detailed data on demand
- **Data Labels**: Clear metric display

## 🎨 Design Elements

### Formatting Standards
- **Consistent Color Scheme**: Professional color palette
- **Typography**: Standardized fonts and sizing
- **Grid Removal**: Clean, minimal design
- **Border Styling**: Clear visual separation
- **Data Label Positioning**: Optimal readability

### Chart Types Used
- **Bar Charts**: Product performance comparison
- **Line Charts**: Trend analysis over time
- **Scatter Plots**: Correlation analysis
- **Map Visualizations**: Geographic distribution
- **Card Visuals**: Key metric display
- **Slicers**: Interactive filtering
- **Tables**: Detailed data views

## 📋 Prerequisites

- Microsoft Power BI Desktop
- Excel workbook with sales data
- Basic understanding of data modeling concepts

## 🔧 Setup Instructions

1. **Data Import**
   - Open Power BI Desktop
   - Click "Get Data" → "Excel Workbook"
   - Select all 4 tables and load data

2. **Data Transformation**
   - Click "Transform Data"
   - Follow data cleaning procedures
   - Create calculated columns as specified
   - Establish table relationships

3. **Dashboard Creation**
   - Build visualizations according to requirements
   - Apply formatting and styling
   - Configure interactive filters
   - Test all functionality

## 📊 Business Value

### Insights Delivered
- **Product Performance**: Identify top and bottom performers
- **Sales Trends**: Understand seasonal patterns and growth
- **Customer Behavior**: Analyze purchasing patterns
- **Promotional Effectiveness**: Measure discount impact
- **Geographic Performance**: Regional sales analysis
- **Profitability Analysis**: Margin optimization opportunities

### Decision Support
- **Inventory Management**: Stock optimization based on performance
- **Marketing Strategy**: Data-driven promotional planning
- **Resource Allocation**: Focus on high-performing segments
- **Pricing Strategy**: Profit margin optimization
- **Market Expansion**: Geographic opportunity identification

---

**Note**: This dashboard is designed for business users with varying levels of technical expertise. All visualizations include intuitive navigation and clear labeling for ease of use.
