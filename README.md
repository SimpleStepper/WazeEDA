# Waze Exploratory Data Analysis (EDA)
## Overview 
This project is part of a larger effort at Waze to increase growth. Typically, high retention rates indicate satisfied users who repeatedly use the Waze app over time. Developing a churn prediction model will help prevent churn, improve user retention, and grow Waze’s business. An accurate model can also help identify specific factors that contribute to churn and answer questions such as: 
* Who are the users most likely to churn?
* Why do users churn? 
* When do users churn? 

This is the continuation of a ongoing project in Googles Advanced Data Analytics Course focusing on the exploratory data analysis of the Waze_dataset provided by Google. The purpose of this project is to conduct exploratory data analysis (EDA) on a provided dataset. The goal is to continue the examination of the data that you began in the previous Course, adding relevant visualizations that help communicate the story that the data tells. 
## Current Project Overview 
1. Data Exploration
2. Data Cleaning
3. Building Visualizations
4. Evaluating and sharing results

Please reference the Jupyter Notebook for more detailed analysis, however key insights are shared below. 
## Quick Insights over project
1. Was there anything that led you to believe the data was erroneous or problematic in any way?
Most of the data was validated through the EDA process. However, many variables had very improbable outlier values, such as driven_km_drives, which had a max of 15,420 KM which is impossible to drive in a day.
Image
It also appears that monthly variables might have mistakes within the data. On activity_days and driving days, one has a max value of 31 days while the other has a max value of 30, which could indicate that the data was not collected within the same month.
Image
2. Did your investigation give rise to further questions that you would like to explore or ask the Waze team about?
Yes, we need to confirm if the data for each variable was collected during the same month. Some values have 30 days, while others have 31 days. It also appears that many long-term members suddenly started using the application in the last month. Why did this occur?

3. What percentage of users churned and what percentage were retained?
~18% of users churned, and ~82% were retained.
image
  
4. What factors correlated with user churn? How?
   Based on the current dataset, KM per Driving Day had a positive correlation with churn rate. The further a user drove had a positive relationship with churn.
   Image
   Number of Driving Days had a negative relationship with churn. User's who drove more days in the month were less likely to churn.
   Image
## Conclusion and Acknowledgement
This project is part of Google's Advanced Data Analytics Professional Certificate Course, specifically as the end-of-course project of the "Go Beyond the Numbers: Translate Data into Insights" sub-course within the broader Google Data Analytics course. All data was provided by google, and the scenario was created with questions to answer. 
