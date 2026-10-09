# Texas Real Estate Market Analysis

## View Full Project Report

📊 [View Complete Analysis on RPubs](https://rpubs.com/Salvo89/1466688)

### Exploratory Data Analysis with R | Statistical Analysis & Data Visualization

## Project Overview

This project analyzes historical real estate market data from four Texas cities between **2010 and 2014**, using R and statistical methods to identify sales trends, market differences, seasonal patterns, and property price distributions.

The analysis was developed around a business case for **Texas Realty Insights**, with the objective of transforming historical market data into meaningful insights to support business decision-making.

## Business Objectives

- Identify historical property sales trends across cities and years.
- Analyze price distributions and market variability.
- Investigate seasonal patterns in real estate sales.
- Compare sales performance and inventory levels across markets.
- Evaluate sales activity relative to active property listings.
- Provide data-driven recommendations for business planning.

## Dataset

The dataset contains **240 observations** representing monthly real estate market activity across four Texas cities:

- Tyler
- Bryan-College Station
- Beaumont
- Wichita Falls

**Period:** January 2010 – December 2014

**Main variables:**
- `city` – City name
- `year` – Year of observation
- `month` – Month of observation
- `sales` – Number of properties sold
- `volume` – Total sales value in millions of USD
- `median_price` – Median property sale price
- `listings` – Number of active property listings
- `months_inventory` – Estimated months of available inventory

## Tools & Technologies

- **R** – Data analysis and statistical calculations
- **RStudio** – Development environment
- **ggplot2** – Data visualization
- **dplyr** – Data manipulation and aggregation
- **R Markdown** – Reproducible analytical reporting
- **knitr** – Statistical table generation and report rendering

## Analytical Methods

### Data Preparation & Validation
- Dataset structure and variable classification
- Missing-value and duplicate checks
- Creation of date variables for time-series visualization

### Descriptive Statistics
- Mean, median and quartiles
- Standard deviation and variance
- Interquartile range (IQR)
- Coefficient of variation
- Skewness and distribution analysis
- Frequency distributions and Gini heterogeneity index

### Exploratory Data Analysis
- Statistical comparisons across cities, months and years
- Sales classification and probability analysis
- Creation of derived indicators, including average property price and sales-to-listings ratio
- Conditional analysis of market performance

### Data Visualization
- Bar charts comparing monthly sales
- Box plots showing price and sales-volume distributions
- Stacked and normalized bar charts
- Faceted charts comparing annual patterns
- Historical sales trend line charts

## Key Findings

**1. Overall Sales Growth**

Total annual property sales increased from **7,878 in 2011 to 11,069 in 2014**, representing approximately **40.5% growth**.

**2. Tyler – Highest Sales Activity**

Tyler recorded the highest overall sales activity, averaging approximately **269.75 property sales per month**, together with the highest median monthly sales volume of approximately **$45.08 million**.

**3. Bryan-College Station – High Prices and Growth**

Bryan-College Station recorded the highest typical property price level, with a median of monthly median prices of approximately **$155,400**, alongside substantial sales growth.

**4. Seasonal Sales Patterns**

Property sales were generally lowest in January and highest in June, with stronger market activity between **May and August**.

**5. Market Variability**

Sales volume showed the greatest relative variability among the quantitative variables, with a coefficient of variation of approximately **53.71%**.

**6. Listings and Inventory**

The median sales-to-active-listings ratio was approximately **10.96%**, providing an indicator of sales activity relative to available inventory.

## Business Recommendations

Based on the historical analysis:

- Consider Tyler and Bryan-College Station for further market investigation due to their sales performance and market characteristics.
- Plan listing and sales activities around historical seasonal demand patterns.
- Adapt pricing approaches to differences between local markets.
- Monitor sales, active listings and inventory together to better understand market conditions.
- Collect additional marketing data to evaluate listing effectiveness more directly.

These recommendations are based on historical observations and should be validated using more recent data.

## Project Limitations

The dataset contains aggregated monthly observations rather than individual property records.

The analysis is descriptive and does not establish causal relationships or predict future market performance. Property prices have not been adjusted for inflation, and marketing effectiveness cannot be measured directly without additional data.

## Repository Files

- `Texas_Real_Estate_Market_Analysis.Rmd` – R code, statistical analysis and visualizations
- `realestate_texas.csv` – Original dataset
- `Texas_Real_Estate_Market_Analysis.html` – Generated analytical report

## Skills Demonstrated

**R Programming | Exploratory Data Analysis | Descriptive Statistics | Data Cleaning & Validation | Data Visualization | Statistical Interpretation | Business Insights | Analytical Reporting**

---

**Author:** Salvatore Spagnolo

**Project Type:** Data Analytics Portfolio Project
