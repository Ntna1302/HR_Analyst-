# HR Analysis

# Introduction

In the intricate landscape of Human Resources Management, our study is particularly focused on the pivotal subject of "Employee Turnover Analysis." This targeted emphasis is carefully chosen to dissect and understand the multifaceted nature of employee attrition and retention through a detailed segmentation approach. Anchoring our analysis is the robust dataset provided by Topica Ed Tech, a rich repository of information that we plan to meticulously analyze to discern patterns and trends in employee turnover.

## Topic Overview

Our objective is to leverage this data to identify key factors that contribute to turnover rates, understand how they vary across different employee clusters, and propose strategic interventions to foster a stable and engaged workforce. Through this initiative, we aspire to provide actionable insights that can significantly reduce turnover and cultivate a more committed and productive organizational environment.

## Data Exploration

Our exploration begins with the "HR_DATA" table, examining metrics like department, division, and employment duration to understand turnover patterns within Topica. The "Turnover Rate per Company Location" allows us to assess the turnover geographically, identifying if certain regions are more affected. Additionally, the "Dim_NG" and "Top 5 Positions in January" focus on specific job roles and their turnover rates, potentially uncovering roles that may require more attention due to higher attrition rates. This targeted analysis of turnover by location and position sets the stage for deeper investigation into the root causes of employee departure.

## Data Design 
![datawh](Image/DataModle.png)
The diagram illustrates an HR database designed to analyze employee turnover. Central to this is the "HR_DATA" table, which connects employee details to other key tables. "Dim_NG" and "Top 5 Positions in January" appear to track turnover by job role and seniority, while "Turnover Rate per Company Location" suggests a focus on the geographic distribution of turnover rates. This schema effectively supports a multifaceted analysis of turnover, allowing for insights that can inform retention strategies.

## Data Mining Techniques Applied to HR Analytics
![datawh](Image/Dax_country.png)
![datawh](Image/Dax_top_5.png)
In our HR analytics project, we employ data mining techniques to identify patterns and gain deeper insights into employee turnover. By leveraging DAX (Data Analysis Expressions), we create calculated measures that allow us to quantify total employees, total turnovers, and calculate turnover rates across various dimensions, such as work locations and time periods.

The "Turnover Rate per Country" measure uses ADDCOLUMNS and SUMMARIZE functions to aggregate turnover data at the country level. This aids in recognizing high-turnover regions and prompts targeted investigations into causal factors.

Another DAX measure, "Top 5 Positions in January," employs CALCULATETABLE, SUMMARIZE, and RANKX functions to rank positions based on turnover rates within a specified timeframe. This helps in pinpointing roles that are at higher risk for turnover at critical times of the year.

By integrating these DAX measures into our data mining process, we derive actionable insights that support strategic HR decision-making, aimed at improving employee retention and satisfaction.

## Business Decision Support:
Our analytics project empowers HR decision-makers by uncovering critical workforce insights. With sophisticated data mining, we spotlight turnover trends and identify key areas for intervention, ultimately supporting strategic decisions to bolster retention and optimize talent management.

## BI dashboard
[](https://app.powerbi.com/groups/me/reports/5ebeef25-9c44-4ce1-b3a0-638253700d76?ctid=a7380202-eb54-415a-9b66-4d9806cfab42&pbi_source=linkShare). ** This dashboard serves as a potent tool for HR professionals, streamlining complex data into intuitive insights. It offers flexible, user-driven analysis options, exemplifying our strategic application of BI tools. This dedication to harnessing data underscores our pursuit of excellence in employee turnover and retention strategies.

# I****nsights, Challenges, and Recommendations****


# Reference 

**Report:** [Report]()

**BI Dashboard:** [PowerBI Dashboard]([https://public.tableau.com/app/profile/nam.nguyen7732/viz/CustomerSegmentationDashboard-RFMAnalysis/Dashboard1?publish=yes](https://app.powerbi.com/groups/me/reports/5ebeef25-9c44-4ce1-b3a0-638253700d76?ctid=a7380202-eb54-415a-9b66-4d9806cfab42&pbi_source=linkShare))



