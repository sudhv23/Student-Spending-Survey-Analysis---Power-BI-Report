# 🛒 Student Spending Survey Analysis - Power BI Report

This Power BI report analyzes student spending patterns across various categories such as video games, indoor/outdoor sports, toys, books, and gadgets. The data originates from a survey conducted in retail stores located in different store settings across the United States.

---

## 📁 Dataset Overview
- **Dataset**: Student Survey
- **Industry**: Retail
- **Key Fields**: Age, Store Location, Store Setting, and spending categories

---

## 📊 Visualizations

### 1. Tabular Visualization
- Displays **Total Amount of Purchase (TAP)** by **Store Location** and **Store Setting**
- Conditional formatting applied:
  - 🔴 Red: TAP < 35,000  
  - 🟡 Yellow: 35,000 ≤ TAP < 60,000  
  - 🔵 Blue: TAP ≥ 60,000  

### 2. Matrix Visualization
- Amount spent on **Outdoor Sports** across different **Ages** and **Store Settings**
- Includes color formatting for total values

### 3. Funnel Chart
- Visualizes **Total Purchase Amount** by **Store Setting**
- Data labels shown as **Percentage of First**

### 4. Pie Chart
- Total purchase by **Store Location** for **Suburban** Store Setting only (filter context applied)

### 5. Scatter Plot
- Comparison between **Video Games Purchase** and **Outdoor Sports Spending** across ages

### 6. Sand Dance Plot *(if supported by installed custom visual)*
- Displays **Indoor Sports** vs **Video Games** spending across different age groups

---

## 💡 Insights
- Age-based and location-based spending behavior
- Identification of top store settings and locations for specific purchase types
- Visual breakdown of how students prioritize various spending categories

---

## 📁 Files Included
- `Student_Survey_Report.pbix`: Power BI Desktop report file
- `Student Survey.xlsx`: Source dataset
