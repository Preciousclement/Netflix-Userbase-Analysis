# Netflix Userbase Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Objectives](#objectives)
- [Steps Taken](#steps-taken)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
  
### Project Overview
This project focuses on analyzing a Netflix userbase dataset, aiming to reveal insights related to subscription types, revenue patterns, and user demographics. 

### Data Source 
The primary data set used for this analysis is "Netflix_Userbase.csv" file from kaggle.com.
The dataset consists of 2,500 rows with attributes such as user ID, subscription type, monthly revenue, join date, last payment date, country, age, gender, device, and plan duration 

### Tools Used
- SQL Server Management Studio- Data Cleaning/Exploration
  - [Download Here](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)
- Power BI - Data visualization and Reporting
  - [Download Here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

### Objectives
1. Data Cleaning: Ensure data integrity by addressing inconsistencies, such as date formatting issues and missing values.
2. Exploratory Data Analysis (EDA): Identify trends and patterns within the data, including user demographics, subscription preferences, and revenue distribution.
3. Visualization: Create visual representations of the insights to facilitate understanding and decision-making.

### Steps Taken
#### 1. Data Cleaning
- Handling Null Values: Identified and addressed any missing or wrong data entries.

#### 2. Exploratory Data Analysis (EDA)
- Subscription Analysis: Analyzed the distribution of different subscription types and calculated the average plan duration for each type.
- Revenue Analysis: Examined monthly revenue trends, including the identification of the highest and lowest revenue-generating subscription types.
- Demographic Analysis: Explored user demographics, including age, gender, and country, to identify key user segments.

#### 3. Visualizations
- Subscription Distribution: Bar charts and pie charts showing the proportion of each subscription type.
- Revenue Trends: Line graphs depicting monthly revenue patterns over time.
- Demographic Breakdown: Heatmaps and bar charts illustrating the distribution of users by age, gender, and country.

### Key Insights
1. Subscription Preferences: Premium subscriptions are the most popular, followed by Basic and Standard plans.
2. Revenue Patterns: There is a consistent monthly revenue stream, with Premium plans contributing the most.
3. Demographics: The majority of users are between the ages of 30-50, with a relatively even distribution across genders. Most users access Netflix via laptops and smartphones.

### Conclusion
This analysis provides a comprehensive overview of Netflix’s userbase, highlighting key trends and areas for potential growth.
The insights can inform marketing strategies, product development, and customer engagement initiatives.

### Recommendations

1. Enhance Targeted Marketing:
  - Focus on users aged 30-50 who prefer Premium subscriptions, as they represent a significant portion of the revenue.
  - Develop region-specific content and promotional strategies, especially in countries with a high concentration of users. Tailoring content to cultural preferences can increase user engagement and retention.

2. Incentivize Longer Subscriptions:
  - Introduce discounts or perks for users who opt for longer subscription durations like 6-month or annual plans. This can reduce churn rates and stabilize revenue streams.
  - Implement loyalty rewards for long-term subscribers

3. Leverage Data Analytics:
  - Develop predictive models to anticipate user behavior, such as likelihood of upgrading or downgrading plans.
  - Conduct regular churn analysis to identify patterns and intervene before users decide to leave the platform.
