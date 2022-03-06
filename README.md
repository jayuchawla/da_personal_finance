# da_personal_finance
Analyzing personal finances and spending using Power BI and Excel analysis techniques.  

## Project Title
#### Analysing personal spending and financial activities.

## Problem Statement
#### Lately, I had a realization about my financial activity and decided to keep a track of it. I decided to analyze my past earnings and spending, and then accordiingly modify my financial activity.  

## Project Goal
-   Embed analytics into daily life.
-   Financial literacy.
-   Practice PowerBI and analytical skills.

## Project Motivation
-   Analyzing then modifying spending pattern.
-   Am I achieving my targets.
-   Judging my financially good/bad months.
-   Analyzing my savings and spending.

## Data Discovery
-   BYOD (Bring your own data)
-   Recorded my financial activity for each month in an excel sheet


## Data Transformation
-   Given data is not in flat format: unpivot data
-   Rename attribute to Month
-   Convert Value column to Fixed decimal type
-   Convert Month column to type Date -> Extract year to new column
-   Convert Year column to text (to use it as a category rather than number)

## Client Requirements
-   Timeline selection (year, month)
-   KPIs for income, networth, savings, spending (varies with timeline chosen)
-   Static KPIs for overall income, networth, savings, spending (does not vary with chosen timeline)
-   Expense and Savings breakdown (in %)
-   Detailed statement (tabular)  
-   Change in expense and saving % with change in income % (mom)

## Building Dashboard
-   Creating KPI measures (Total Income, Total Savings, Total Expenses, Expense %, Savings %)
-   Creating static KPI measures (all time)
-   Creating slider (year and month)
-   Creating clustered bar chart for Total Expenses (in %) by Component (House rent, emi, ..)
-   Creating clustered bar chart for Total Savings (in %) by Component (Mf, fd, ..)
-   Creating Expenses Trend (new page) over time (line chart) and attach as tooltip for above clustered bar chart.
-   Creating Savings Trend (new page) over time (line chart) and attach as tooltip for above clustered bar chart.
-   _Creating a multi line chart which helps visualizing Savings Change MoM %, Expenses Change MoM % against Income Change MoM %._