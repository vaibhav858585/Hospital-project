# Hospital-project

🏥 Emergency Hospital ER Dashboard – Power BI Project

This project presents a comprehensive Power BI dashboard designed to analyze and monitor key performance indicators of an Emergency Hospital Department.
It provides real-time insights into patient flow, waiting times, satisfaction score, demographic trends, referral patterns, and hourly visit distribution.

The dashboard helps hospital management make data-driven decisions to improve emergency care efficiency and patient experience.


Project Objectives

Monitor total patient visits and monthly trends

Reduce emergency room waiting time

Identify bottlenecks in patient flow

Track patient demographics to optimize resources

Analyze referral departments and peak visiting hours

Improve patient satisfaction and service quality


Key Features & Insights
1️⃣ Total ER Visits

Shows the number of patients visiting the Emergency Room for the selected month.

2️⃣ Average Waiting Time

Displays the average time patients wait before being attended.

3️⃣ Patient Satisfaction Score

Overall satisfaction rating based on patient feedback.

4️⃣ Referral Analysis

Breakdown of patients referred from:

General Practice

Orthopedics

Cardiology

Physiotherapy

Neurology

Gastroenterology

Or no referral

5️⃣ Patients Seen Within 30 Minutes

Percentage of patients seen within the hospital’s target time.

6️⃣ Admission Status

Admitted

Not admitted

7️⃣ Demographic Insights

Detailed breakdown by:

Age group

Gender

Race

8️⃣ Hourly & Daily Visit Heatmap

Identifies peak days and hours to allocate staff efficiently



Total Patients = COUNTROWS(Patient_Data)

Average Wait Time = AVERAGE(Patient_Data[WaitTime])

Patients Seen Within Target = 
CALCULATE(COUNTROWS(Patient_Data), Patient_Data[WaitTime] <= 30)

Satisfaction Score = AVERAGE(Patient_Data[Rating])


How to Use

Clone/download the repository

Open the .pbix file in Power BI Desktop

Use the slicers (Month, Year) to explore insights

View trends, KPIs, charts, and heatmaps interactively


Conclusion

This dashboard helps hospitals:

Improve ER service delivery

Optimize staffing and resource allocation

Reduce wait times

Enhance patient satisfaction

Identify critical patterns in emergency care

It is a complete, real-world Healthcare Analytics Project suitable for portfolio, job interviews, and internship applications.


