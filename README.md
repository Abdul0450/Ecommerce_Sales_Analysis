# Ecommerce Sales Analysis

This repository contains the Power BI project for analyzing ecommerce sales data. The project aims to provide insights into sales performance, customer behavior, and payment mode trends. The analysis is based on two data tables: `details` and `order`.

## Project Overview

### Data Tables
- **Details Table:**
  - Columns: `Order ID`, `Amount`, `Profit`, `Quantity`, `Category`, `Sub-Category`, `Payment Mode`
- **Order Table:**
  - Columns: `Order ID`, `Order Date`, `Customer Name`, `State`, `City`

### Key Features
- **Data Integration:**
  - Merged the `details` and `order` tables using the common `Order ID` field.
- **Sales Performance:**
  - Visualized total sales, profit, and quantity sold across different categories and sub-categories.
- **Customer Insights:**
  - Analyzed customer distribution by state and city to identify key markets.
- **Payment Mode Analysis:**
  - Evaluated the popularity and performance of different payment methods.
- **Time-Based Analysis:**
  - Tracked sales trends over time to identify seasonal patterns and peak sales periods.

## Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-sales-analysis.git
