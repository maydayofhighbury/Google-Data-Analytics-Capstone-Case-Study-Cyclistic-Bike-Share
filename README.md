# Google Data Analytics Capstone Case Study: Cyclistic Bike-Share

## Introduction
In this project, I take on the role of a junior data analyst for Cyclistic, a fictional bike-share company in Chicago. The goal is to analyze rider data and provide actionable insights to help Cyclistic attract more riders and convert casual users into annual members.

Throughout the case study, I follow the six steps of the data analysis process:
1. Ask: Define the business problem and key questions.
2. Prepare: Collect and review the relevant data.
3. Process: Clean and organize the data for analysis.
4. Analyze: Explore the data to identify trends and patterns.
5. Share: Visualize and communicate findings.
6. Act: Make recommendations based on the analysis.

This case study simulates real-world tasks and collaboration within a marketing analytics team. It includes guiding questions and key tasks to ensure a structured approach. The final deliverable is a portfolio-ready project that demonstrates my ability to apply data analysis skills to solve business problems—an excellent addition to showcase to potential employers.

All project materials, including data cleaning steps, analysis, visualizations, and recommendations, are documented in this repository.

## Table of Contents
- [Business Task](#business-task)
- [Data Sources](#data-sources)
- [Data Analysis Process](#data-analysis-process)
    - [1. Ask](#1-ask)
    - [2. Prepare](#2-prepare)
    - [3. Process](#3-process)
    - [4. Analyze](#4-analyze)
    - [5. Share](#5-share)
    - [6. Act](#6-act)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Tools Used](#tools-used)
- [Project Structure](#project-structure)

---

## Business Task
Cyclistic’s marketing team wants to better understand how annual members and casual riders use their bike-share service. The main goal is to identify differences in usage patterns and develop actionable recommendations to convert casual riders into annual members.

**Key Question:**  
How do annual members and casual riders use Cyclistic bikes differently?

---

## Data Sources
- [Cyclistic Bike-Share Data](https://divvy-tripdata.s3.amazonaws.com/index.html) (12 months of historical trip data in CSV format)
- Data columns include: `ride_id`, `rideable_type`, `started_at`, `ended_at`, `start_station_name`, `end_station_name`, `member_casual`, etc.

---

## Data Analysis Process

### 1. Ask
- **Business Task:** Identify usage patterns to help convert casual riders to annual members.
- **Stakeholders:** Cyclistic Marketing Director, Analytics Team, Executive Team.

### 2. Prepare
- Downloaded 12 months of trip data.
- Reviewed data structure and key columns.
- Checked for data quality issues such as missing values and inconsistencies.

### 3. Process
- Removed duplicate records and rows with missing critical information.
- Standardized column formats (e.g., dates and member types).
- Created new columns for ride duration and day of the week.

### 4. Analyze
- Used pivot tables and charts (in Excel/Google Sheets) to compare:
    - Number of rides by member type
    - Average ride duration by member type
    - Most popular days of the week for each group
    - Most common start and end stations
- Identified key differences in usage patterns between annual members and casual riders.

### 5. Share
- Created visualizations (bar charts, line graphs, pie charts) to illustrate findings.
- Summarized insights in this README and included sample charts in the `/visuals` folder.

### 6. Act
- Developed recommendations for marketing strategies to encourage casual riders to become annual members.
- Documented the entire process, findings, and recommendations in this repository.

---

## Key Findings
- **Casual riders** tend to use bikes more on weekends and for longer durations.
- **Annual members** are more likely to use bikes on weekdays and for shorter, more frequent trips.
- Certain stations are more popular among casual riders, suggesting opportunities for targeted promotions.

---

## Recommendations
- **Targeted Marketing:** Promote membership benefits at stations and times popular with casual riders.
- **Special Offers:** Introduce weekend or event-based membership discounts.
- **Enhanced Communication:** Use email or app notifications to highlight savings and perks of annual membership.

---

## Tools Used
- Microsoft Excel / Google Sheets (data cleaning, analysis, and visualization)
- Tableau Public / Google Data Studio (optional, for advanced visualizations)
- Markdown (for documentation)

---

## Project Structure
```
Cyclistic-Case-Study/
│
├── data/
│   └── (Cleaned data files)
├── visuals/
│   └── (Charts and graphs)
├── README.md
└── Cyclistic_Case_Study_Summary.pdf (optional)
```

---

## How to Use This Repository
1. **Explore the data** in the `/data` folder.
2. **Review the analysis and visuals** in the `/visuals` folder.
3. **Read this README** for a summary of the process, findings, and recommendations.
4. **Use or adapt this case study** as a portfolio piece for your own job search.

---

## Acknowledgments
- Google Data Analytics Professional Certificate
- Cyclistic (Fictional Company)
- Divvy Bike-Share (Real-world data provider)

---

**This case study demonstrates my ability to apply the data analysis process to a real-world business problem and communicate actionable insights to stakeholders.**
