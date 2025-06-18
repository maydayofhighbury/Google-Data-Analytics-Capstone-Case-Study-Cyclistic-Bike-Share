# Cyclistic Bike-Share Case Study: How Does a Bike-Share Navigate Speedy Success?

## Introduction
  This project is part of my independent learning for the Google Data Analytics Capstone on Coursera. In this case study, I take on the role of a junior data analyst on the Cyclistic marketing analytics team. The goal is to analyze historical bike trip data to understand how annual members and casual riders use Cyclistic bikes differently, and to support the development of marketing strategies to convert casual riders into annual members.
---

## Business Task
  Cyclistic’s director of marketing has identified the need to maximize the number of annual memberships for future growth. My task is to analyze usage differences between annual members and casual riders and provide data-driven recommendations to help convert casual riders into annual members.
---

## Key Questions
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?
---

## Data Sources
- Cyclistic historical trip data: 12 months of bike trip data provided for the case study (CSV format).
- Key columns: `ride_id`, `rideable_type`, `started_at`, `ended_at`, `start_station_name`, `end_station_name`, `member_casual`, etc.
- Data privacy: No personally identifiable information is included, in accordance with privacy guidelines[1].
---

## Data Preparation
- Downloaded the previous 12 months of Cyclistic trip data.
- Organized files into folders for original and working datasets.
- Opened CSV files in Excel/Google Sheets and saved as spreadsheet files for analysis.
- Created new columns:
  - `ride_length`: Calculated as `ended_at` minus `started_at`.
  - `day_of_week`: Calculated using the date of each ride’s start time.
- Ensured consistent formatting and checked for missing or duplicate data[1].
---

## Data Processing
- Removed duplicates and rows with missing critical data.
- Standardized date, time, and member type columns.
- Verified data integrity through sorting, filtering, and summary statistics.
- Documented all cleaning steps for reproducibility[1].
---

## Analysis Approach
- Aggregated data by user type (`member_casual`) to compare usage patterns.
- Calculated descriptive statistics (mean, max, count) for ride length and ride frequency.
- Used pivot tables to analyze:
  - Average ride length by user type and day of week.
  - Number of rides by user type and day of week.
- Merged monthly data for a full-year view and exported summary files for visualization.
---

## Sharing Results
- Created visualizations (bar charts, line graphs, etc.) to compare annual members and casual riders.
- Focused on clear, accessible presentation of findings, using appropriate labels and formatting.
- Included all visualizations and summary tables in the `/visuals` folder of this repository.
---

## Key Findings
- (Insert your actual findings here after analysis, e.g.: “Annual members tend to take shorter, more frequent rides on weekdays, while casual riders take longer rides, often on weekends.”)
- (Summarize any notable trends or differences you discovered.)
---

## Recommendations
Based on the analysis, my top three recommendations are:
1. (Insert your recommendation #1, e.g.: “Promote membership benefits at stations and times popular with casual riders.”)
2. (Insert your recommendation #2, e.g.: “Offer targeted digital promotions to frequent casual riders.”)
3. (Insert your recommendation #3, e.g.: “Highlight cost savings and convenience of membership in digital campaigns.”)
---

## Tools Used
- Excel or Google Sheets (data cleaning, analysis, visualization)
- Markdown (documentation)
- (Optional: Tableau, Google Data Studio, or other visualization tools)
---

## Repository Structure
```
Cyclistic-Case-Study/
│
├── data/
│   └── (Cleaned data files)
├── visuals/
│   └── (Charts and graphs)
├── README.md
```
---

## About This Project
- Completed independently as part of the Google Data Analytics Capstone on Coursera.
- All analysis and recommendations are based on the provided dataset and case study instructions.
- No confidential or personally identifiable information is included.
---

**This project demonstrates my ability to follow a structured data analysis process (Ask, Prepare, Process, Analyze, Share, Act) and communicate actionable insights for real-world business questions.**
---

*For more details, see the official case study instructions provided by Coursera and referenced in this repository.*
