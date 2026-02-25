# PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS

##   Project Overview
Remote health noticed an increase in missed and cancelled appointments that impacts continuity of care and revenue. This report outlines the steps taken to analyze engagement patterns, understand why patients miss appointments, data driven engagement strategies.

## Table of Content
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Tasks](#tasks)
- [Deliverables](#deliverables)
- [Datasets](#datasets)
- [Methodology](#Methodology)
- [Answer to Questions](#answer-to-questions)
- [Recommendations](summary-and-recommendations)

## Tools Used
- Microsoft Power BI
  
- Microsoft Excel

## Tasks
1.	Calculate completion, missed, and cancellation rates
2.	Segment patients by engagement level
3.	Identify high-risk disengaged patients
4.	Visualize appointment trends
5.	Recommend engagement improvements

## Deliverables 
•	Engagement metrics table
•	Visual dashboards
•	Engagement insight report
•	Retention strategy recommendations

## 1.	Clean and merge datasets
I copied the patients and consultations dataset from the link provided https://docs.google.com/document/d/1WRah5zfdE4vy5bz3XOFIBx_0YjWxtL_BYkmxKOBxSmo/edit?usp=sharing and pasted it on Microsoft Excel worksheet, after which I saved the documents. Then I opened my Microsoft Power BI to get the patients and consultations datasets I saved from Ms. Excel, it loaded to the power query where I was able to clean, transform and merge both datasets.

## Datasets
![image alt](https://github.com/JoshuaGee-bit/PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS/blob/main/Consultations%20Dataset.jpg)
![image alt](https://github.com/JoshuaGee-bit/PATIENT-HEALTH-RISK-ANALYSIS-AND-STRATIFICATION-REPORT/blob/main/Patients%20Dataset.jpg)

## Merged Dataset
![image alt](https://github.com/JoshuaGee-bit/PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS/blob/main/Merged%20Dataset.jpg)

## 2. Calculate completion, missed, and cancellation rate
To get the missed, cancelled and completion rate. I created a measure for each of them using the DAX queries below to get them.

![image alt](https://github.com/JoshuaGee-bit/PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS/blob/main/Completed%20Appointment.jpg)
![image alt](https://github.com/JoshuaGee-bit/PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS/blob/main/Cancelled%20Appointment.jpg)
![image alt](https://github.com/JoshuaGee-bit/PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS/blob/main/Missed%20Appointment.jpg)

## 3. Segment Patient by Engagement Level	
To segment patients by engagement level, I created a calculated column using the DAX query below.

![image alt](https://github.com/JoshuaGee-bit/PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS/blob/main/Engagement%20Level.jpg)

## 4.	Identify high-risk disengaged patients. 
To identify high risk disengaged patients. I also created a calculated column and used the query below to get it.

![image alt](https://github.com/JoshuaGee-bit/PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS/blob/main/High%20Risk%20Disengagement.jpg)

## 5. Visualize appointment trends.
I created an interactive dashboard that showed total, completed, missed and cancelled appointment, completion and missed appointment rates with visual cards. Charts containing Total appointment by status, missed appointments by age group, total and completed appointments by consult type, missed group by age group, slicers containing gender, status, location, consult type, date, age group, patient id by engagement level. 

![image alt]()






