# 📊 Data Professionals Survey Dashboard — Power BI Project

## 📌 Project Overview
This project builds a fully interactive Power BI dashboard using real-world survey data collected from data professionals on LinkedIn. 

The goal was to transform raw survey responses into a clean, visually compelling dashboard that reveals key insights about salaries, job satisfaction, and career trends in the data industry.

## 📂 Dataset

- **Source:** Real LinkedIn survey collected by Alex The Analyst
- **Respondents:** 630 data professionals
- **Fields include:** Job title, salary, country, programming language preference, work/life balance rating, salary satisfaction rating, difficulty breaking into data, and more


## 🛠️ Tools Used

- **Power BI Desktop:** data transformation (Power Query), data modelling, DAX, and dashboard design


## 🔍 Project Workflow
1. **Data Transformation in Power Query**
    - Loaded raw survey data into Power Query Editor
    - Split and cleaned multi-value columns (e.g. job title and salary range columns that contained extra text)
    - Removed irrelevant columns to simplify the data model
    - Calculated average salary from salary range text fields using custom columns
    - Standardised inconsistent entries in job title, country, and programming language columns

2. **Data Visualisations Built**
    - **Stacked Bar Chart:** Average salary by job title
    - **Treemap:** Country of survey respondents
    - **Donut Chart:** Favourite programming language by job title
    - **Gauge Chart:** Average happiness with work/life balance (out of 10) and average happiness with salary (out of 10)
    - **Card KPIs:** Total survey takers & average age of respondents
    - **Bar Chart:** Difficulty of breaking into data

3. **Dashboard Design**
    - Arranged all visuals into a single-page, clean dashboard
    - Applied consistent colour theme and formatting throughout
    - Added a title and summary KPI cards at the top for quick insights


## 📈 Key Insights

- Data Scientists earn the highest average salary among all data roles
- Python is by far the most popular programming language across all job titles
- The average work/life balance satisfaction score was 5.74 / 10
- The average salary satisfaction score was 4.27 / 10: suggesting many professionals feel underpaid
- The majority of respondents found breaking into data "neither easy nor difficult" or "difficult"
- United States had the largest share of survey respondents


## 💡 Key Power BI Skills Demonstrated
- **Power Query:** Data cleaning, column splitting, custom columns
- **DAX:** Calculated measures for averages and KPIs
- **Data Visualisation:** Bar charts, treemap, donut, gauge, cards
- **Dashboard Design:** Single-page layout with consistent theme
- **Data Modelling:** Clean schema after transformation

## 📁 Repository Structure
├── README.md

├── data/

│   └── Power BI - Final Project.xlsx    # Raw survey data

└── dashboard/

│    └── Final_Project.pbix               # Power BI dashboard file

## 🚀 How to Reproduce

1. Download Power BI Desktop for free at powerbi.microsoft.com
1. Clone or download this repository
1. Open dashboard/Final_Project.pbix in Power BI Desktop
1. All data is embedded — no external connections needed
1. Explore the dashboard and interact with the visuals


## 🖼️ Dashboard Preview
<img width="1311" height="733" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/8f91c0c3-a37a-4911-9c9d-27c0c20ab762" />


## 👤 Author

### Sofia Costa

https://www.linkedin.com/in/sofiassvcosta/

https://github.com/soda-sil
