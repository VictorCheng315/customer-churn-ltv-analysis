# Customer Churn & LTV Analysis

## Overview
This project explores anonymized customer transaction data to study revenue concentration, construct churn indicators, and approximate lifetime value (LTV). It provides a foundational view of customer retention analysis.

## Objectives
- Identify Pareto concentration: what percentage of customers generate most revenue.
- Build a simple customer-level dataset with revenues and churn flags.
- Provide baseline insights into customer LTV and churn risk.

## Methods
- Aggregate revenue per customer.
- Pareto analysis (80/20 rule).
- Construct churn dataset (`churn_data`) for retention studies.

## Key Insights
- About 27% of customers contribute roughly 80% of total revenue.
- High customer concentration risk: losing top customers can significantly impact sales.
- Baseline churn indicators prepared for future predictive modeling.

## Project Structure
This repo includes both the `.Rmd` source file and the rendered `.html` report.
Open the `.Rmd` file in RStudio and knit it to reproduce results.

## Technologies
- R (tidyverse, dplyr, ggplot2)
- Exploratory data analysis
