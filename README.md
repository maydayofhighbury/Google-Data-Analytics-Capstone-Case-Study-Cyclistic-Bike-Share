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

This case study simulates real-world tasks and collaboration within a marketing analytics team. It includes guiding questions and key tasks to ensure a structured approach. The final deliverable is a portfolio-ready project that demonstrates my ability to apply data analysis skills to solve business problems - an excellent addition to showcase to potential employers.

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

**Key Questions:**  
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

---

## Data Sources
- [Cyclistic Bike-Share Data](https://divvy-tripdata.s3.amazonaws.com/index.html) (12 months of historical trip data in CSV format)
- Data columns include: `ride_id`, `rideable_type`, `started_at`, `ended_at`, `start_station_name`, `end_station_name`, `member_casual`, etc.

---

## Data Analysis Process
### 1. Ask
- Defined the three business questions above in collaboration with the Cyclistic marketing team.

### 2. Prepare
- Downloaded and reviewed 12 months of trip data.
- Assessed data quality, structure, and relevance for the analysis.

### 3. Process
- Cleaned the data by removing duplicates and rows with missing values.
- Standardized date and member type formats.
- Calculated ride duration and extracted day of week for each trip.

### 4. Analyze
- Used pivot tables and charts to compare ride frequency, duration, and timing by user type.
- Identified behavioral trends and patterns.
- Researched potential motivators for membership.
- Explored digital marketing strategies relevant to Cyclistic’s goals.

### 5. Share
- Created visualizations (bar charts, line graphs, pie charts) to illustrate findings.
- Summarized insights and recommendations in this README.

### 6. Act
- Developed actionable recommendations for Cyclistic’s marketing team, focusing on digital media engagement.

---

## Findings & Answers

### 1. Usage Patterns

**How do annual members and casual riders use Cyclistic bikes differently?**
- **Annual members** typically use bikes for short, frequent trips during weekdays, suggesting commuting or routine travel.
- **Casual riders** are more likely to take longer rides on weekends and holidays, indicating recreational or leisure usage.
- Certain stations and times are more popular with casual riders, highlighting opportunities for targeted outreach.

### 2. Motivations for Membership
**Why would casual riders buy Cyclistic annual memberships?**
- **Cost savings:** Frequent riders can save money with a membership versus paying per ride.
- **Convenience:** Members enjoy streamlined access and exclusive perks.
- **Promotions:** Limited-time discounts or bundled offers can incentivize sign-ups.
- **Personalization:** Highlighting how membership fits individual usage patterns (e.g., for weekend explorers or daily commuters).

### 3. Digital Media Strategies
**How can Cyclistic use digital media to influence casual riders to become members?**
- **Targeted Ads:** Use social media and search ads focused on popular casual rider locations and times.
- **Personalized Emails:** Send follow-up emails to casual riders with personalized usage stats and membership offers.
- **Content Marketing:** Share stories, tips, and benefits of membership on the Cyclistic blog and social platforms.
- **Referral Programs:** Encourage current members to invite friends with digital referral bonuses.
- **App Notifications:** Use in-app messages to promote membership benefits right after a casual ride.

---

## Tools Used
- Microsoft Excel / Google Sheets (data cleaning, analysis, visualization)
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
1. Review the data in the `/data` folder.
2. Explore the analysis and visuals in the `/visuals` folder.
3. Read this README for a summary of the process, findings, and recommendations.
4. Use or adapt this case study as a portfolio piece for your own job search.
---

## Acknowledgments
- Google Data Analytics Professional Certificate
- Cyclistic (Fictional Company)
- Divvy Bike-Share (Real-world data provider)

---

**This case study demonstrates my ability to apply the data analysis process to a real-world business problem and communicate actionable insights to stakeholders.**
