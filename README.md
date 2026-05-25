# Interactive Business Analytics Dashboard in Blazor

A comprehensive business analytics dashboard built with Blazor components. This project demonstrates modern data visualization techniques including responsive [dashboard](https://www.syncfusion.com/blazor-components/blazor-dashboard), [interactive charts](https://www.syncfusion.com/blazor-components/blazor-charts), [datagrid](https://www.syncfusion.com/blazor-components/blazor-datagrid), and dynamic filtering for real-time business insights.

## Features

- **Dashboard Layout**: Responsive, resizable panels for flexible UI organization
- **Sales Analytics**: Multi-colored line chart tracking revenue trends over time
- **Geographic Distribution**: Bar chart visualizing order counts across countries
- **Product Performance**: Interactive data grid with sorting and filtering capabilities
- **KPI Cards**: Real-time display of key metrics (revenue, orders, customers, retention rate)
- **Date Range Filtering**: Dynamic date picker to filter all dashboard data by custom time periods
- **Responsive Design**: Mobile-friendly layout with Bootstrap 5 integration

## Overview

This dashboard provides business intelligence capabilities for analyzing:

- **Sales Trends**: Visual representation of revenue patterns over time with color-coded data points
- **Order Distribution**: Geographic breakdown of order volumes across 10+ countries
- **Product Insights**: Top-selling products with detailed metrics including pricing, units sold, and total sales
- **Customer Metrics**: Active customer count and retention rate analytics

The dashboard refreshes dynamically when users select a new date range, providing instant insights across all visualizations.

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/interactive-business-analytics-dashboard-in-blazor-with-syncfusion.git
cd BADashboardBlazor
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```


## Dashboard Components

### KPI Cards (Panel 1-4)
Display critical business metrics with visual icons:
- Total Revenue
- Total Orders
- Active Customers
- Customer Retention Rate

### Sales Revenue Trends (Panel 5)
Interactive line chart showing monthly revenue patterns with:
- Multi-colored data points
- Data labels on hover
- Visible markers for easy tracking

### Country-wise Order Distribution (Panel 6)
Bar chart comparing order volumes across 10 countries, useful for:
- Market analysis
- Regional performance evaluation

### Top Selling Products (Panel 7)
Data grid with interactive features:
- **Columns**: Product ID, Name, Category, Unit Price, Units Sold, Total Sales
- **Features**: Excel-style filtering, sorting, responsive columns

## Technology Stack

- **Framework**: ASP.NET Core with Blazor Server
- **Styling**: Bootstrap 5
- **Language**: C# 12 with nullable reference types

## Data

The dashboard includes sample data for demonstration:
- **Monthly Sales**: 12 data points covering January to December 2024
- **Country Orders**: Distribution across 10 countries
- **Products**: 10 product entries with pricing and sales metrics

Date filtering works within the range of January 1, 2024 to December 31, 2024.

## References

- [ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Blazor Documentation](https://docs.microsoft.com/en-us/aspnet/core/blazor/)
- [Blazor charts and data visualization concepts](https://towardsdev.com/bringing-your-data-to-life-f6e80e68748d)


