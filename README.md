# Diagnostic-Analysis-using-Python
Licensed under CC BY-NC-ND 4.0. View the LICENSE file for details.

Diagnostic analysis and presenting key insights to address problem faced by NHS( in depth technical report can be found in [01 Project Management](01%20Project%20Management/)

## Project description
The project's goal was to assess how best to allocate budgets with an overall question of whether the NHS should expand its capacity or make better utilisation of available resources.The two initial questions that have been asked by the NHS are:

- Has there been adequate staff and capacity in the networks?
- What was the actual utilisation of resources?

## Data Sources(s)
Provided was five data files, actual_duration.csv,appointments_regional.csv,national_categories.xlsx,metadata_nhs.txt and tweets.csv
## Research questions
Analysis focused on asking several questions both of key stakeholders as well as the data: 
- What is the number of locations, service settings, context types, national categories, and appointment statuses in the data sets?
- What is the date range of the provided data sets, and which service settings reported the most appointments for a specific period?
- What is the number of appointments and records per month?
- What monthly and seasonal trends are evident, based on the number of appointments for service settings, context types, and national categories?
- What are the top trending hashtags (#) on the supplied Twitter data set and how can this be used in the decision-making process?
- Was there adequate staff and capacity in the networks?
- What was the actual utilisation of resources?
- What insights can be gained by looking at missed appointments?
- What insights can be gained from the data, and what recommendations can be made to the NHS based on these insights?
## Juypter notebook
Cleaned up my working document to adhere to good practices and added comments to the code and observations as markdown cells where appropriate.

## End Results and Recommendations
### **Strategic Recommendations**

- **Healthcare Resource Utilization:**
    - Allocate additional staff during winter periods to address decreased utilization capacity (0.7).
- **Missed Appointments and Capacity Issues:**
    - Review October appointment capacity to address overwhelming demand that leads to missed appointments.
    - Implement automated appointment reminders via SMS and phone calls to reduce missed appointments.
- **Anomalies in Data:**
    - Investigate and correct data entry errors that categorize occupations under 'Other Practice Staff' to ensure accurate reporting and analysis.
- **Resource Allocation:**
    - During high-demand periods (e.g., October 2021), increase non-face-to-face appointment options to alleviate strain on resources.
    - Plan resource allocation with seasonal trends in mind, including boosting Primary Care Networks to provide more localized and coordinated care.
- **Social Media Analysis:**
    - Monitor high-engagement critical tweets to understand public sentiment and address concerns effectively.
    - Focus on #healthcare trends (785 mentions) to gauge public interest and tailor communication strategies accordingly.

## **Outcomes and Impact**

These recommendations improve resource utilization, reduce missed appointments, enhance decision-making through accurate data, and optimize patient care during peak periods. Leveraging social media insights fosters public trust, resulting in better healthcare outcomes, operational efficiency, and strengthened NHS perception.

## Reflections

- There is room for improvement in comparing data by using scaling, normalization, or separate plots to better identify patterns when values vary significantly.
- Observations could be expanded to include contextual insights, such as missed appointments as a percentage or the impact of external events.

## **Next Steps**

- Incorporate scaling or normalization techniques to enhance comparative analysis of data.
- Expand contextual analysis to include percentages and external factors influencing observed patterns.
- Align observations and suggested actions directly with business goals and include detailed explanations of assumptions, risks, and methodologies.
