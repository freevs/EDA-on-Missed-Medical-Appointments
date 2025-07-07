# EDA on Missed Medical Appointments

![Alt Text](https://media.istockphoto.com/id/1473559425/photo/female-medical-practitioner-reassuring-a-patient.jpg?s=612x612&w=0&k=20&c=kGbm-TE5qdppyyiteyip7_CzKLktyPrRuWD4Zz2EcqE=)

## Goal
The goal of this project is to analyze over 110k  medical appointments from the public health system to understand the key factors contributing to patient no-shows. By uncovering patterns in the data, the project aims to provide actionable insights that can help clinics reduce missed appointments, optimize scheduling, and improve patient care.

## Steps Performed
**Data Acquisition & Understanding**
* Sourced the dataset from Kaggle, including features such as appointment dates, patient demographics, neighborhood, chronic conditions, welfare program participation, and SMS reminders.
* Explored dataset structure and clarified attribute meanings.

**Data Cleaning & Wrangling**
* Checked for and removed invalid entries (e.g., negative ages, scheduling after appointment date).
* Converted ID columns to string types for consistency.
* Created a new feature: waiting_days (days between scheduling and appointment).
* Standardized categorical variables and fixed typos in neighborhood names.

**Exploratory Data Analysis**
* Calculated overall no-show rates and visualized the distribution.
* Analyzed no-show rates by waiting time, neighborhood, age group, chronic conditions, and SMS reminders.
* Used heatmaps and bar charts to highlight trends and high-risk areas.
* Assessed class balance and patient attendance patterns.

## Key Insights
* About 20% of appointments were missed (~22,000 out of 110,000+).
* No-show rates increased from 10% for same-day appointments to over 30% for appointments scheduled a month ahead.
* Some neighborhoods had no-show rates as high as 40%, while others were below 10%.
* Elderly patients and those with chronic conditions were more likely to attend; younger and healthier patients had higher no-show rates.
* Patients who received reminders were 15% more likely to attend.
* A small group of patients accounted for multiple missed appointments.

## Recommendations
* Shorten the gap between scheduling and appointment date to decrease the likelihood of no-shows, especially for non-urgent visits.
* Prioritize sending reminders to patients with longer waiting times, those in high-risk neighborhoods, and those with a history of missed appointments.
* Investigate and address barriers in neighborhoods with the highest no-show rates—this could include transportation support, flexible scheduling, or local outreach.
* Identify and monitor patients who have missed multiple appointments, and consider additional follow-up or support for these individuals.
* Continuously track no-show patterns and the effectiveness of interventions using dashboards and regular data reviews.


