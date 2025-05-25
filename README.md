# espn-cricket-analytics

### Dashboard Link : https://app.powerbi.com/groups/me/reports/5d72242a-0233-4de1-beee-b8ecf1a21bf1/72e9ba0080cadd8598a5?experience=power-bi

## Problem Statement

This dashboard helps cricket analysts, fans, and team strategists gain a deeper understanding of individual and team performances in a structured,it explore detailed performance insights of India and South Africa players by scraping data directly from ESPN Cricinfo. visual format. It provides powerful insights into batting, bowling, and fielding performances by scraping data directly from ESPN Cricinfo.

It highlights areas like:
- Top run scorers, strike rates, and consistency in batting

- Wicket-taking ability, economy, and averages in bowling

- Key fielders and their impact in fielding

- DAX functions like RANKX, LOOKUPVALUE, and ABS were used to add depth, such as ranking players and categorizing them by performance.

This dashboard solves the problem of scattered cricket data by turning it into a centralized, insightful, and easy-to-use analysis tool.


### Steps followed 

Project Planning & Requirement Understanding

Identified key objectives: analyze batting, bowling, and fielding data for India & South Africa.

Defined KPIs and visualization goals for the dashboard.

Web Scraping Using Power BI

Imported HTML tables directly from ESPN Cricinfo for batting, bowling, and fielding stats.

Scraped separate data for both teams.

Data Cleaning & Column Definition

Renamed and structured columns for clarity.

Removed null values and irrelevant data rows.

Standardized formats for numerical and categorical data.

Data Transformation using Power Query

Applied transformations like trimming, replacing values, changing data types, and creating calculated columns.

Creating Calculated Columns using DAX

Used LOOKUPVALUE to map category values.

Applied RANKX to rank players based on performance.

Used POWER and ABS for performance metrics.

Designing the Dashboard

Created separate pages for Batting, Bowling, and Fielding Analysis.

Added slicers, span cards, and performance indicators.

Applied formatting for a clean, interactive user experience.

Publishing to Power BI Service

Published the dashboard for online access and sharing.

Enabled filter options and responsive visuals for better analysis.

Snapshot of Dashboard (Power Bi Service)

Batting:

![Image](https://github.com/user-attachments/assets/63e7ecd0-4413-44e1-9666-18139d2a7acf)

Bowling:

![Image](https://github.com/user-attachments/assets/c1109c40-df7b-4099-8d26-b46a39283eb9)

Fielding:

![Image](https://github.com/user-attachments/assets/1e4f54c4-e59e-4555-946e-b2e41fa4336f)




