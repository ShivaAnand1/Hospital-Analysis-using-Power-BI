Hospital Patient Analysis Dashboard
This repository contains a Power BI dashboard and the corresponding dataset used for deep-dive analysis of hospital patient data from Nomula's Hospital. The project is designed to help healthcare professionals and administrators better understand patient demographics, treatment outcomes, resource utilization, and key operational metrics.

Project Overview
The goal of this project is to leverage Power BI for visualizing, exploring, and generating insights from hospital patient records. The dashboard enables stakeholders to make informed decisions by analyzing trends in admissions, costs, patient satisfaction, recovery outcomes, and more.

Dashboard Features
The dashboard includes condition by total cost, which visualizes total costs incurred by different medical conditions to help identify costliest treatments. It features admissions analysis with a breakdown of patient admissions by year, state, and medical condition for resource planning. Length of stay trends track how the average length of hospital stay varies by year of admission. Readmission analytics identify readmission rates split by gender and by month to aid patient care improvements. Medication outcome analysis shows the proportion of patients recovered or stable after treatment. Patient satisfaction covers average patient age segmented by satisfaction scores. Cost and demographic correlations use scatter and categorical analysis to find relationships between patient age, condition, and costs. Geographical distribution provides a map view of patient admissions by Indian state, highlighting regional healthcare needs.

Dataset
The dataset (Hospital-Patient.csv) consists of anonymized patient records from 2022 to 2025. Key columns include Patient ID, Age, Gender, Condition, Medication, Admission & Discharge Dates, State, Length of Stay, Readmission, Treatment Outcome, Satisfaction, Insurance Claimed, Total Cost, and more.

Files Included
The repository includes Hospital-Dashboard.pbix, which is the Power BI dashboard file for interactive analytics and reporting, and Hospital-Patient.csv, which is the dataset used for all dashboard visualizations.

Usage
Download or clone this repository. Open Hospital-Dashboard.pbix with Power BI Desktop. Load the Hospital-Patient.csv file if prompted. Explore the interactive visuals to gain insights into patient outcomes, costs, satisfaction, and operational patterns.

Insights & Example Questions Answered
The dashboard answers questions such as which conditions are generating the highest costs for the hospital, how readmission rates vary across genders and months, which patient groups report the highest satisfaction, and whether there are particular states with higher patient inflow or specific treatment patterns.

Getting Started
To reuse or extend the dashboard, replace Hospital-Patient.csv with your own data while keeping column headers consistent. Open the Power BI file and refresh data. Customize visuals and queries as needed for your specific analysis or report.

License
This repository is licensed under the MIT License. Please anonymize real patient data before public sharing.
