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
