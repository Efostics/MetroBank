# METROBANK BRANCH PERFORMAMCE ANALYSIS

<img width="893" height="498" alt="Screenshot 2025-09-22 094226" src="https://github.com/user-attachments/assets/2ee77e1a-47fa-4c76-882c-c0bb6f577504" />

### Introduction
This project analyzes the performance and efficiency of MetroBank’s 15 branches. Understanding branch performance is key to maximizing profitability and ensuring operational success. By examining financial and operational patterns, this analysis aims to guide the Chief Operating Officer (COO) in deciding where to invest, streamline, or close branches, keeping MetroBank competitive and sustainable.

### Problem Statement
MetroBank faces varying branch performances, raising the question:
- "Why are some branches thriving while others are struggling?"

This project tackles this challenge by addressing key questions:
- Which branches and regions are the most profitable?
- How efficiently are staff utilized across branches?
- Are high operating costs justified, and which branches are underperforming?
The goal is to identify patterns and recommend actions to boost efficiency and profitability.

### Data Overview
The dataset, sourced from the Week 4 "Branches" CSV file provided in the MetroBank Strategists briefing, includes records for 15 branches. It contains columns for BranchID, Region, City, Staff_Count, Operating_Cost, and Revenue.

### Methodology
Step 1: Data Cleaning and Transformation
Tools: Power Query (Excel)
- Removed duplicates and ensured consistent data types (e.g., numeric for Revenue, Operating_Cost).
- Added calculated columns:
Profit = Revenue - Operating_Cost

Revenue_per_Employee = Revenue / Staff_Count

Cost_to_Revenue_Ratio = Operating_Cost / Revenue

Step 2: Analysis and Dashboard Creation

Tools: Powerpoint and Power BI visualization features
- Designed an initial layout using Powerpoint.
- Built an interactive dashboard with filters for Region and BranchID.
- Used bar charts, a scatter plot (Revenue vs. Staff_Count), and cards (key metrics) to highlight trends.
