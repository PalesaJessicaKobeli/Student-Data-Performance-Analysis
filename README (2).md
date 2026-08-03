# Student Performance Analysis — Idealnovate

## Project Overview
This project analyzes a student performance dataset (~1,000 records) covering demographics, socio-economic indicators, and academic scores across math, reading, and writing. The dataset was cleaned and explored, then visualized in an interactive **Power BI** dashboard titled *Student Performance Dashboard*.

This is **Project 1** in a series of data analysis projects.

## Dataset

| Column | Description |
|---|---|
| `gender` | Encoded gender (0 / 1) |
| `race_ethnicity` | Student ethnic group (group A–E) |
| `parental_level_of_education` | Highest education level attained by a parent (e.g., High School, Some College, Associate's/Bachelor's/Master's Degree) |
| `lunch` | Lunch type indicator (0 / 1 — e.g., standard vs. free/reduced) |
| `test_preparation_course` | Whether the student completed a test prep course (0 = no, 1 = yes) |
| `math_score` | Math exam score (0–100) |
| `reading_score` | Reading exam score (0–100) |
| `writing_score` | Writing exam score (0–100) |
| `total_score` | Sum of math, reading, and writing scores |
| `average` | Average of the three subject scores |

**Records:** ~1,000 students
**Format:** Tabular data (originally CSV/Excel), exported here as PDF alongside the dashboard.

## Dashboard Highlights (Power BI)

- **Math Score by Gender** — bar chart comparing total math scores between gender groups (Group 0: 32,962 · Group 1: 33,127)
- **Intelligence (Total Score) by Ethnicity** — bar chart of summed total scores per ethnic group:
  - Group A: 16,819
  - Group B: 37,317
  - Group C: 64,245
  - Group D: 54,375
  - Group E: 30,556
  - **Grand Total:** 203,312
- **Ethnicity Distribution (Donut Chart)** — share of students by group:
  - Group C: 319 (31.9%)
  - Group D: 262 (26.2%)
  - Group B: 190 (19%)
  - Group E: 140 (14%)
  - Group A: 89 (8.9%)
- **KPI Cards:**
  - Sum of Total Score: 203K
  - Sum of Gender: 482
  - Sum of Average: 67.77K

## Key Insights
- Group C is the largest ethnic segment in the dataset (nearly a third of all students) and also contributes the highest combined total score.
- Total math scores are fairly balanced between the two gender groups, with only a small gap (~165 points across ~1,000 students).
- Score totals by ethnicity broadly track group size, suggesting per-student performance is relatively consistent across groups rather than driven by outliers.

## Tools Used
- **Power BI Desktop** — data modeling, DAX measures, and dashboard visualization
- Source data exported/reviewed as PDF for documentation purposes

## Files
- `Student_Data_File_3_Palesa_project_1_Idealnovate_.pdf` — raw dataset export and Power BI dashboard visuals
- `README.md` — this file

## Author
Palesa

## Status
Completed — Project 1 of the data analysis series
