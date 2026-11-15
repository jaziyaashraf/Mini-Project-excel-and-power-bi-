# Screen Time, Sleep & Academic Performance Analysis | Excel & Power BI Mini Project

## 1. Project Overview

The **Screen Time, Sleep & Academic Performance Analysis** is an interactive data analytics project developed using Microsoft Excel and Power BI. The project focuses on analyzing student demographics, screen-time habits, sleep patterns, and academic performance.

The main objective is to transform raw student data into meaningful information through data preparation, data cleaning, analysis, and interactive visualizations.

The project explores three major areas:

1. Student Profile and Overview
2. Screen Time and Sleep Analysis
3. Academic Performance

The final report consists of three interactive dashboard pages, allowing users to explore student information and compare different indicators through KPI cards, charts, and slicers.

## 2. Project Objectives

The main objectives of this project are:

- Analyze student demographics and population distribution.
- Understand students' daily screen-time habits.
- Explore screen-time and sleep patterns.
- Analyze academic performance using CGPA and attendance.
- Compare academic indicators across study years and chronotypes.
- Explore student lifestyle patterns and their relationship with academic indicators.
- Present meaningful information through interactive dashboards.
- Develop practical data analytics and visualization skills.

## 3. Dataset Information

The project uses a student dataset containing demographic, lifestyle, sleep-related, and academic information.

**Dataset Details:**
- Total Records: 500 students
- Domain: Student Analytics and Education
- Analysis Tool: Microsoft Power BI

### Dataset Columns

| Category | Columns |
|---|---|
| Student Profile | student_id, age, gender |
| Education | year_of_study, major_category |
| Residence | residence_type |
| Lifestyle | chronotype, caffeine_drinks_per_day, exercise_days_per_week |
| Screen Time | daily_screen_time_hours, pre_sleep_screen_time_min, primary_device |
| Sleep | avg_bedtime_hour, avg_sleep_hours_weekday, sleep_quality_score |
| Academic | cgpa, class_attendance_percent, weekly_study_hours |

Additional columns include weekend_sleep_delta_hours, device_free_before_bed, naps_per_week, energy_level, concentration_difficulty, has_part_time_job, and semester_type.

## 4. Data Preparation and Cleaning Using Excel

Microsoft Excel was used during the initial stage of the project to review, organize, and prepare the student dataset for analysis.

### Activities Performed in Excel

- Opened and reviewed the original student dataset.
- Examined the dataset structure and column names.
- Checked the data for missing and inconsistent values.
- Reviewed numerical and categorical columns.
- Identified data-quality issues.
- Prepared the dataset for further cleaning and analysis.

### Data Cleaning Using Power Query

Power Query was used for data cleaning and transformation.

The cleaning process included:

- Reviewing missing and null values.
- Checking inconsistent categorical values.
- Standardizing gender-related entries.
- Reviewing numerical columns and decimal values.
- Identifying unusual values and potential outliers.
- Checking and correcting data types.
- Preparing the cleaned dataset for Power BI visualization.

After data preparation and cleaning, the dataset was used for further analysis and dashboard development.

## 5. Tools and Technologies Used

### Microsoft Excel
Used for initial dataset review, data preparation, and handling the student dataset.

### Power Query
Used for cleaning, transforming, and preparing the dataset for analysis.

### Microsoft Power BI Desktop
Used for developing interactive dashboards, creating visualizations, and presenting analytical findings.

### DAX (Data Analysis Expressions)
Used for creating measures and calculating key performance indicators (KPIs) in Power BI.

## 6. Dashboard Development

The Power BI report contains three pages, each focusing on a different area of student analytics.

### Page 1: Student Overview

**Purpose:** Provides a high-level overview of the student population and demographic distribution.

**Key Performance Indicators (KPIs):**

- Total Students: 500
- Part-Time Job Members: Count of students with part-time jobs
- Number of Majors: 7

**Visualizations:**

1. Student Count by Residence Type – Pie Chart
2. Student Count by Study Year – Bar Chart
3. Student Count by Gender – Pie Chart
4. Student Count by Major Category – Treemap
5. Part-Time Job Count by Study Year – Bar Chart

**Interactive Slicer:**
- Gender

**Analysis Focus:**

This page helps users understand student distribution based on gender, residence type, study year, and major category.

It also provides an overview of students with part-time jobs across different study years.

### Page 2: Screen Time and Sleep Analysis

**Purpose:** Explores students' daily screen-time habits and sleep-related indicators.

**Key Performance Indicators (KPIs):**

- Average Daily Screen Time: 5.83
- Average Bedtime Hour: 12.78
- Average Sleep Quality: 7.27

**Visualizations:**

1. Daily Screen Time Hours vs. Average Weekday Sleep Hours by Student ID – Scatter Chart
2. Average Daily Screen Time Hours by Study Year – Bar Chart
3. Average Weekday Sleep Hours by Chronotype – Bar Chart
4. Average Pre-Sleep Screen Time (Minutes) by Screen-Time Category – Bar Chart

**Interactive Slicer:**
- Major Category

**Analysis Focus:**

This page helps users explore screen-time habits and sleep patterns across different student groups.

The scatter chart displays student-level screen-time and weekday sleep-hour values together.

Other visualizations compare average screen time and sleep measures across study years, chronotypes, and screen-time categories.

### Page 3: Academic Performance

**Purpose:** Analyzes academic indicators and compares student performance across different groups.

**Key Performance Indicators (KPIs):**

- Average CGPA: 2.84
- Average Attendance: 79.25
- Average Weekly Study Hours: 16.57
- Average Exercise Days: 3.67

**Visualizations:**

1. Average CGPA by Class Attendance Percentage – Scatter Chart
2. Average CGPA by Chronotype – Bar Chart
3. Average CGPA by Study Year – Bar Chart
4. Average CGPA and Average Weekly Study Hours by Study Year – Combo Chart

**Interactive Slicer:**
- Study Year

**Analysis Focus:**

This page provides an overview of academic performance through CGPA, attendance, and study-hour indicators.

Users can compare average CGPA across study years and chronotypes and explore academic indicators among different student groups.

## 7. Key Performance Indicators Summary

| Dashboard Page | KPI | Value |
|---|---|---:|
| Student Overview | Total Students | 500 |
| Student Overview | Part-Time Job Members | Actual card value |
| Student Overview | Number of Majors | 7 |
| Screen Time & Sleep | Average Daily Screen Time | 5.83 |
| Screen Time & Sleep | Average Bedtime Hour | 12.78 |
| Screen Time & Sleep | Average Sleep Quality | 7.27 |
| Academic Performance | Average CGPA | 2.84 |
| Academic Performance | Average Attendance | 79.25 |
| Academic Performance | Average Weekly Study Hours | 16.57 |
| Academic Performance | Average Exercise Days | 3.67 |

*Note: The part-time job member count should be updated with the actual value from the Power BI card. Units and exact measure definitions should be confirmed from the underlying calculations.*

## 8. Power BI Features and Visualizations

The following Power BI features were used to develop the report:

| Feature | Purpose |
|---|---|
| Card Visuals | Display important KPIs |
| Pie Charts | Show category distributions |
| Bar Charts | Compare values across groups |
| Treemap | Display student distribution by major |
| Scatter Charts | Explore relationships between numerical measures |
| Combo Chart | Compare CGPA and weekly study hours |
| Slicers | Filter report data interactively |
| Cross-filtering | Explore related information by selecting chart elements |

## 9. Dashboard Interactivity

The report includes interactive features that allow users to explore student data.

- Navigate between the three dashboard pages.
- Filter student information using available slicers.
- Select chart elements to cross-filter or highlight related visuals.
- Compare student groups across different categories.
- Clear selections to return to the overall report view.

## 10. How to Use the Dashboard

1. Open the Power BI report using Microsoft Power BI Desktop.
2. Navigate through the three report pages using the page tabs at the bottom.
3. Select the required slicer category.
4. Explore the charts and KPI cards.
5. Select chart elements to view related information.
6. Clear the filters or selections to return to the overall view.

## 11. Key Analytical Areas

### Student Demographics
- Student population distribution.
- Gender distribution.
- Residence and major-category distribution.
- Part-time employment across study years.

### Screen Time and Sleep Patterns
- Average daily screen time.
- Pre-sleep screen-time distribution.
- Sleep duration across chronotypes.
- Student-level screen-time and sleep-hour distribution.

### Academic Performance
- Average CGPA across study years.
- CGPA comparison across chronotypes.
- Attendance and CGPA distribution.
- Weekly study hours and academic performance.

These visualizations support exploratory analysis of student data. They show patterns and comparisons but do not independently establish causal relationships.

## 12. Project Limitations

- The analysis is based on 500 student records.
- Dashboard values depend on the available dataset and applied calculations.
- The report represents patterns and comparisons within the dataset.
- Additional student records could provide broader insights.
- The bedtime-hour metric requires its time-format definition for accurate interpretation.

## 13. Future Enhancements

- Add more detailed student performance analysis.
- Explore relationships between sleep quality and academic performance.
- Compare screen-time categories with sleep duration.
- Add advanced DAX measures.
- Improve drill-through functionality.
- Incorporate additional student datasets for comparative analysis.

## 14. GitHub Repository Structure

```text
Student-Analytics-Dashboard/
│
├── README.md
│
├── Student_Analytics_Dashboard.pbix
│
├── Dataset/
│   └── Student_Screen_Time_Dataset.csv
│
└── Screenshots/
    ├── Student-Overview.png
    ├── Screen-Time-and-Sleep-Analysis.png
    └── Academic-Performance.png
```

*Replace the example filenames with the actual filenames used in your project.*

## 15. Project Summary

The **Student Analytics Dashboard** is an interactive data analytics project that brings together student demographics, screen-time habits, sleep patterns, and academic performance in a single report.

The project involves preparing and cleaning student data using Microsoft Excel and Power Query, followed by developing interactive visualizations using Microsoft Power BI.

Through KPI cards, charts, slicers, and interactive filtering, the dashboard provides an organized way to explore student information and identify patterns across different student groups.

This project demonstrates practical skills in:

- Data Preparation
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Dashboard Development
- Power BI Reporting

**Project Title:** Screen Time, Sleep & Academic Performance Analysis

**Project Type:** Data Analytics Mini Project

**Domain:** Student Analytics and Education

**Tools Used:** Microsoft Excel, Power Query, and Microsoft Power BI
