# Flu Vaccination Analysis Project
This project analyzes flu vaccination data in Massachusetts for 2022 using PostgreSQL for data processing and Tableau for visualization. It identifies patterns and insights into vaccination rates, helping to evaluate public health efforts.

## Project Features
### Data Sources:
Patient demographics (age, race, county, etc.).
Immunization records for 2022.
Encounter history to identify active patients.

### Analysis Objectives:
Calculate vaccination percentages stratified by age, race, and county.
Track the running total of flu shots administered month-by-month in 2022.
Determine the total number of flu shots given in 2022.
Generate a list of patients indicating whether they received a flu shot.

### Data Filtering Criteria:
Patients must have had at least one encounter within the last three years.
Patients must be alive.
Patients must be at least six months old as of December 31, 2022.

### Implementation Highlights:
SQL queries process the data in PostgreSQL.
Common Table Expressions (CTEs) streamline intermediate filtering and calculations.
Tableau visualizes the results with dynamic and interactive dashboards.

### Insights Provided:
Trends in vaccination uptake across demographics.
Identification of regions or groups with lower vaccination rates.
Overview of vaccination coverage in the population.

## Tools and Technologies
Database: PostgreSQL
Visualization: Tableau

## Usage
Run the SQL script in your PostgreSQL database to prepare the processed dataset.
Use the Tableau workbook (Flu_Project.1.twb) to visualize the analysis.

## About
This project was created to explore flu vaccination trends and support public health efforts through data-driven insights.
