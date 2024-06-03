# Healthcare Waitlist Dashboard

## Overview
This repository contains a Power BI dashboard that visualizes healthcare waitlist data. The dashboard provides insights into the total wait list, case type split, time bands vs. age profile, top specialties, and monthly trends for day case and inpatient vs. outpatient.

## Project goals:
1. track current status of patient waiting list
2. Analyze historical monthly trend of waiting list in inpatient and outpatient categories.
3. Detailed speciality level and age profile analysis.

## Data scope:
2018-2021

## Metrics Required:
1. Average and median waiting list.
2. Current total wait list.

## Views required:
1. Summary Page
2. Detailed Page for Granular analysis.

## Preprocess Steps:
#### Check all the CSV files for column count and column name similarity.
#### Use the folder connector to load data into Power BI.
#### Transform the data using a power query editor. Check the column types and count the rows.
#### Do necessary checks for appending the datasets.
#### Append two tables.
#### Make a bucket for specialty and load it then map it in the data model.
#### Design blueprint of the dashboard.

## Key Metrics and Visualizations

### Summary
- **Total Wait List Comparison**:
  - **Latest Month Wait List** vs **Previous Year Latest Month Wait List**
  - **Purpose**: Compare the total number of patients on the wait list between the current month and the same month in the previous year.

- **Case Type Split**:
  - **Outpatient**
  - **Day Case**
  - **Inpatient**
  - **Purpose**: Visualize the distribution of cases by type with a donut chart.

- **Time Bands vs. Age Profile**:
  - **Visualization**: A bar chart showing average/median wait list across different age groups and time bands.
  - **Purpose**: Identify patterns and trends in wait times based on age groups and duration of wait.

- **Top 5 Specialties**:
  - **Specialties**: Accident & Emergency, Paed Cardiology, Paed Orthopaedic, Paediatric Dermatology, Paediatric ENT.
  - **Purpose**: Highlight the specialties with the highest average/median wait list.

### Monthly Trend Analysis
- **Day Case/Inpatient vs. Outpatient**:
  - **Visualization**: Line charts showing monthly trends for day cases, inpatients, and outpatients from 2018 to 2021.
  - **Purpose**: Analyze trends over time for different case types. Tooltips can show details of any point in time.

### Detailed Breakdown
- **Case Type, Specialty Name, Age Profile, and Time Bands**:
  - **Visualization**: A detailed table showing the breakdown of day cases, inpatients, and outpatients across different specialties, age profiles, and time bands.
  - **Purpose**: Provide an in-depth view of the data for more granular analysis.

## Key Insights
- **Increasing Wait List**: The total wait list has increased from 640K in the previous year to 709K in the latest month, indicating a growing demand for healthcare services.
- **Dominance of Outpatient Cases**: Outpatient cases constitute the majority (72.49%) of the total cases, followed by inpatient and day cases.
- **Age and Wait Time Correlation**: Older age groups (65+) tend to have longer wait times, especially in the 18+ months category.
- **Top Specialties with High Wait Times**: Accident & Emergency and Paediatric specialties (Cardiology, Orthopaedic, Dermatology, ENT) have the highest average wait lists, highlighting potential areas for capacity improvement.
- **Seasonal Trends**: Monthly trend analysis reveals seasonal fluctuations, with notable peaks in specific months for both day cases and outpatients.

## Setup and Usage
1. Clone the repository to your local machine.
2. Open the Power BI file `Healthcare Power BI Dashboard.pbix` in Power BI Desktop.
3. Ensure that the data connections are updated if necessary.
4. Use the slicers and filters to interact with the dashboard and explore the data.
