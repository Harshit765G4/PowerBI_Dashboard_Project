# HR Analytics Dashboard

The **HR Analytics Dashboard** is a dynamic and interactive Power BI project designed to provide actionable insights into key HR metrics. It leverages advanced visualizations and data analytics techniques to analyze employee data and provide HR professionals with valuable information for decision-making.

---

## Overview

This dashboard includes:
- **Key Metrics**: Quick insights into overall employee count, attrition rate, active employees, and average age.
- **Interactive Visuals**: Includes pie charts, bar charts, donut charts, matrix heat maps, and more.
- **Dynamic Filters**: Allows users to filter data based on attributes like education level, department, and age group.
- **Comprehensive Analysis**: Visualizes department-wise attrition, age group demographics, job satisfaction ratings, and education field-wise attrition.

---

## Key Features

### **1. KPIs**
The dashboard displays critical Key Performance Indicators (KPIs) such as:
- Overall Employee Count
- Attrition Rate
- Active Employee Count
- Average Age

### **2. Charts**
Various charts are used to visualize and analyze data effectively:
- **Pie Chart**: Attrition by department
- **Stacked Bar Chart**: Employees by age group and gender
- **Donut Charts**: Attrition rate by gender for different age groups
- **Frequency Charts**: Education field-wise attrition

### **3. Slicers & Filters**
- Dynamic filters allow users to explore data based on custom criteria.
- Automatically updates all visualizations upon filter application.

---

## Data Preparation

### **Data Connection**
- The dashboard connects to a dataset with ~1500 rows and multiple columns.

### **Data Transformation**
- **Power Query Editor**: Applied transformations like setting headers, creating conditional columns, and sorting age groups.
- Tracks all transformation steps for easy modification.

---

## Metrics Calculation

### **Attrition Count**
A new column was created to count employees who left the company.

### **Attrition Rate**
The attrition rate was calculated using the formula:
Attrition Rate (%) = (Attrition Count / Total Employee Count) * 100


---

## Dashboard Visualizations

1. **Pie Chart**: Department-wise attrition analysis.
2. **Frequency Chart**: Employee count by age group and gender.
3. **Donut Charts**: Gender-specific attrition rate for different age groups.
4. **Matrix Heat Map**: Job satisfaction ratings across different roles.
5. **Bar Chart**: Education field-wise attrition.

---

## Design Highlights

- **Single-Page Layout**: All visuals are presented on a single cohesive canvas.
- **KPI Cards**: Metrics are formatted for clarity and visual appeal.
- **Sorting & Conditional Columns**: Age groups and other attributes are sorted for better readability.

---

## Getting Started

### **Prerequisites**
1. Power BI Desktop installed on your machine.
2. A dataset in `.csv` or `.xlsx` format (matching the format used in this dashboard).

### **Steps to Use**
1. Clone this repository to your local machine.
2. Open the `.pbix` file in Power BI Desktop.
3. Load your dataset into Power BI.
4. Explore and interact with the dashboard visuals.

---

## How to Contribute

We welcome contributions! If you'd like to improve this project:
1. Fork this repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## Acknowledgments

Special thanks to the contributors who made this project possible!

Also a special mention to "DATA TUTORIALS" Youtube channel from where I take out help from their Tutorials.
