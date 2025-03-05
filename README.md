# INSURANCE DATA ANALYSIS
## Dashboard Link: 
https://app.powerbi.com/links/x20dV7qpz9?ctid=8bf89164-b311-40ca-a295-2e0f5f39d14e&pbi_source=linkShare
## Problem Statement: 
To conduct a comprehensive analysis of Prism Insurance Private Limited’s insurance policies, claims by various metrics to identify key insights using various visualizations and KPIs in Power BI.
## Business Requirements: 
1.	Total premium amount and how it varies with policy number, claim number, gender and customer id
2.	Total claim amount and how it varies with policy number, claim number, gender and customer id
3.	Total coverage amount and how it varies with policy number, claim number, gender and customer id
4.	Total no of claims under various claim status and how they vary with policy number, claim number, gender and customer id
5.	Total claim amount by age group and how they vary with policy number, claim number, gender and customer id
6.	Total premium amount by policy type and how they vary with policy number, claim number, gender and customer id
7.	Total no of active/inactive policies and how they vary with policy number, claim number, gender and customer id
8.	Total coverage amount of various claim status under different policy types. 
## Steps Followed:
1.	The data was imported to Power BI desktop in excel format. Data quality was checked in Power Query Editor after having changed column profiling to view entire dataset. A new column was added named ‘Age Group’ using conditional column where people between age 18-24 were placed under the category of ‘Young Adult’, less than 60 under ‘Adult’ or else under ‘Senior’. The datatype of the column was changed to text.
2.	Three slicers were added to present policy number, customer id and claim number as filters.
3.	Three card visuals were added to represent total claim amount, total premium amount and total coverage amount.
4.	A bar chart was added to represent premium amount by policy type.
5.	A donut chart was added to represent division of active and inactive policies.
6.	A table was added to view total coverage amount of various claim status under different policy types.
7.	A multi-row card was added to represent gender as filters.
8.	A ribbon chart was added to represent no of claims by various claim status.
9.	A line chart was added to represent claim amount by age group.
10.	Finally, dashboard was completed and published to Power BI.
## Key Findings:
1.	The travel sector had the highest premium amount followed closely by health and auto.
2.	Inactive policies were more in number than active however there wasn’t a huge difference between the two.
3.	Adults had the highest claim amount followed by senior and then young adults.
4.	Rejected claims were more in number than selected and pending.
5.	The two genders had almost same data available for all the metrics. So there was nothing to separate them.

![Image Alt](image_url)
