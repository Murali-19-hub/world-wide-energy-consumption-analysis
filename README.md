# World Wide Energy Consumption Analysis | MySQL

## Project Overview

This project analyzes global energy consumption, energy production, GDP, population, and emissions using MySQL. The objective is to explore relationships between economic growth, energy usage, and environmental impact through SQL queries and data-driven analysis.

## Project Objectives

- Analyze country-wise and year-wise emission trends.
- Identify countries with the highest GDP and emissions.
- Compare energy production and consumption across countries.
- Examine relationships between population, economic output, and emissions.
- Calculate energy consumption and emissions relative to GDP.
- Analyze changes in global emissions over time.
- Generate meaningful insights using SQL-based analysis.

## Tools & Technologies

- **MySQL** — Database management and querying
- **SQL** — Data extraction, transformation, and analysis
- **Common Table Expressions (CTEs)** — Structuring complex queries
- **Window Functions** — Year-over-year comparisons and ranking
- **Joins & Subqueries** — Combining related datasets
- **Aggregate Functions** — Summarizing energy, economic, and demographic data

## Database Overview

The project uses six related tables:

- `country` — Country reference data
- `emission_3` — Country-wise emissions, energy types, and years
- `population` — Population figures by country and year
- `production` — Energy production by country, energy type, and year
- `gdp_3` — GDP values by country and year
- `consumption` — Energy consumption by country, energy type, and year

The tables are connected through country identifiers or country names, with year-based joins used for time-aligned analysis.

## SQL Analysis Performed

### 1. Emissions Analysis
- Calculated total emissions by country for the latest available year.
- Ranked energy types by total emissions.
- Analyzed global year-over-year emission changes.
- Compared emissions across highly populated countries.

### 2. Economic Analysis
- Identified the top five countries by GDP in the latest available year.
- Examined GDP trends across countries and years.
- Compared GDP and emissions to explore economic and environmental relationships.

### 3. Energy Consumption & Production
- Compared energy production and consumption by country, year, and energy type.
- Analyzed consumption trends among major economies.
- Calculated energy consumption per capita.
- Examined energy consumption relative to GDP.

### 4. Population & Per Capita Analysis
- Compared population and emissions across countries.
- Calculated emission and energy consumption ratios relative to population.
- Examined per-capita emission changes between selected years.

### 5. Advanced SQL Techniques
- Joins across multiple related tables
- Nested queries and subqueries
- Common Table Expressions (CTEs)
- Window functions such as `LAG()` and `DENSE_RANK()`
- Grouping, aggregation, sorting, and filtering
- Ratio calculations and year-over-year comparisons

## Key Findings

- Global emissions increased each year from 2020 to 2023 in the analyzed dataset.
- China recorded the highest total emissions in the latest emission year analyzed, 2023.
- China ranked first in the latest GDP year analyzed, 2024.
- Energy consumption relative to GDP highlighted differences in energy intensity across countries.
- Comparing population, GDP, energy usage, and emissions provided complementary perspectives on global energy and environmental patterns.

## Challenges & Learnings

- Working with multiple related tables and aligning country-year records.
- Handling different year coverage across datasets.
- Translating analytical questions into SQL queries.
- Applying joins, CTEs, subqueries, and window functions to real-world datasets.
- Interpreting query results and communicating findings clearly.

## Project Files

- `world_wide_energy_consumption_analysis.sql` — Database setup, table definitions, and analytical SQL queries.
- `World_Wide_Energy_Consumption_Presentation.pptx` — Project presentation containing selected queries, outputs, and key findings.

## Disclaimer

This project is intended for educational and portfolio purposes. Findings reflect the supplied dataset and the years available for each indicator.

## Author

**Murali Krishna Reddy**
