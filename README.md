# Task 3: Exploratory Data Analysis (EDA) Project 📊

## Overview
This repository contains my structured EDA report for Task 3 of the data science internship. The objective was to perform exploratory data analysis on a real-world dataset to uncover hidden patterns, calculate statistical summaries, and identify key influencing factors.

*Context: Developed concurrently with TSSM BSCOER SPPU 2024 syllabus coursework.*

## Dataset Selection & Feature Engineering
I utilized the **Restaurant Dining & Tips Dataset** to analyze human behavioral trends regarding spending and tipping habits. 
- **Analytical Thinking Applied:** Instead of solely looking at the raw tip amount, I engineered a new feature called `tip_percentage` `(tip / total_bill * 100)`. This provides a much more accurate metric for generosity across different bill sizes.

## Key Insights & Influencing Factors
Based on the generated `eda_insights_dashboard.png` and `statistical_summary.txt`, I uncovered the following trends:

1. **Strongest Correlation (Bill vs. Tip):** As expected, the correlation heatmap shows a strong positive correlation (0.68) between the total bill and the tip amount. The regression scatter plot confirms this linear upward trend.
2. **Time & Day Patterns:** Weekend dinners (Saturday and Sunday) generate the highest average tips compared to Thursday/Friday lunches. 
3. **The "Party Size" Paradox:** While larger party sizes leave larger *total* tips, the boxplot reveals that the **tip percentage actually decreases** as the party size grows. Solo diners and couples tend to tip a higher percentage of their bill than groups of 5 or 6.

## Repository Assets
- `Task3_EDA_Project.ipynb`: Complete Python source code for data manipulation and visualization.
- `statistical_summary.txt`: Exported mathematical summary of the dataset (mean, quartiles, min/max).
- `eda_insights_dashboard.png`: A 4-panel visual report containing a regression plot, bar chart, boxplot, and correlation heatmap.
