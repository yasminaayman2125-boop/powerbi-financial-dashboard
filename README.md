# powerbi-financial-dashboard
Financial Performance Dashboard – Power BI

Project Overview

This project presents a Financial Performance Dashboard built using Power BI to analyze business financial data.
The dashboard helps visualize performance trends and compare Actual, Budget, and Forecast values across time, entities, and product categories.

The goal of this project is to transform raw financial data into interactive insights that help decision-makers understand business performance.


 Tools: 

- Power BI
- Data Modeling
- DAX Measures
- Data Visualization


 Dataset Structure:

The dataset follows a star schema model with fact and dimension tables.

 Fact Table:

FactStrategyPlan

  - Amount
  - AccountKey
  - CurrencyKey
  - DateKey
  - EntityKey
  - ProductCategoryKey
  - ScenarioKey

 Dimension Tables

- DimDate → date and time attributes
- DimAccount → financial account details
- DimEntity → business entities
- DimProductCategory → product category information
- DimScenario → Actual / Budget / Forecast scenarios

Dashboard Features

KPI Cards:

- Total Actual Amount
- Total Budget Amount
- Total Forecast Amount

Line Chart:

Shows financial performance over time using a Date hierarchy (Year - Quarter - Month - Day).

Category Analysis:

A Tree Map / Bar Chart showing revenue distribution across product categories.

 Interactive Slicers:

Users can filter the dashboard by:

- Year
- Quarter
- Entity
- Scenario
- Product Category
- Budget
- Forecast

Key Insights:

The dashboard enables users to:

- Track financial trends over time.
- Compare Actual vs Budget vs Forecast performance.
- Identify top-performing product categories.
- Analyze performance by business entity.


 Dashboard Preview:

Example:



