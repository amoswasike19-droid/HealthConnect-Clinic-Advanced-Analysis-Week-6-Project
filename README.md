HealthConnect Clinic – Week 6 Analytics & Insights

📌 Project Overview

HealthConnect Clinic is working to improve patient appointment attendance and healthcare support by using data and AI.

This Week 6 project builds on the Week 5 analysis by moving beyond initial exploratory analysis into Advanced Analytics & Decision Support. The focus is on validating important findings, identifying deeper patterns associated with appointment no-shows, improving analytical outputs, and providing evidence that can support the development of a patient no-show risk model.

Track: Analytics & Insights
Project: Improving Patient Appointment Attendance and Healthcare Support Using Data and AI
Tools: Power BI, DAX, Excel
Dataset: HealthConnect Appointment Dataset


---

🎯 Project Objectives

The Week 6 analysis aimed to:

Deepen the most important findings identified during Week 5.

Validate key KPIs and analytical findings.

Investigate relationships between previous no-show history, reminders, booking lead time, and appointment type.

Identify potential risk factors that could support Data Science modelling.

Translate analytical findings into practical business actions.

Improve the Power BI analytical report.

Provide evidence for the next stage of project testing and development.



---

📊 Week 5 Foundation

Week 5 established the initial analytical foundation through data preparation, exploratory data analysis, KPI development, and visualization.

Important Week 5 findings included:

Overall appointment no-show rate: 48.46%

Reminder effectiveness rate: 47.63%

Previous no-show rate: 18.06%

Average booking lead time: 29.6 days

Longer booking lead times were associated with higher no-show rates.

Patients with previous no-shows were more likely to miss their current appointments.


Week 6 builds on these findings rather than repeating the Week 5 analysis.


---

🔎 Advanced Analytics

1. Previous No-Show History and Reminders

Patients with 1+ previous no-shows had a current no-show rate of 55.41%, compared with 43.51% among patients with no previous no-shows.

The analysis also showed lower no-show rates among patients who received reminders:

0 previous no-shows: 42.80% with reminders vs 45.44% without.

1+ previous no-shows: 53.83% with reminders vs 59.55% without.


This suggests that previous no-show history is an important potential risk indicator and that reminders may be useful as part of targeted attendance-support strategies.

2. Booking Lead Time and Reminders

No-show rates increased as the booking lead time became longer:

Booking Lead Time	No-Show Rate

0–7 Days	27.81%
8–14 Days	33.55%
15–30 Days	43.21%
31–60 Days	60.49%


Reminded appointments had lower no-show rates within each lead-time group.

3. Appointment Type and Previous No-Show History

Previous no-show history was associated with higher no-show rates across all appointment types.

Among patients with 1+ previous no-shows:

Follow-up: 56.78%

Diagnostic Test: 56.47%

General Consultation: 55.26%

Specialist Consultation: 52.78%


This indicates that patient history may be useful when identifying higher-risk appointment groups.

4. Validated Reminder Relationship

The overall no-show rate was:

47.36% when a reminder was sent.

51.39% when no reminder was sent.


This represents a 4.03 percentage-point difference.

These results show an association, not proof that reminders directly caused the reduction in no-shows.


---

📈 Power BI Dashboard

The Week 6 Power BI Advanced Analytics page includes:

No-Show Rate by Previous History and Reminder Status

No-Show Rate by Booking Lead Time and Reminder Status

No-Show Rate by Appointment Type and Previous No-Show History

Validated No-Show Rate by Reminder Status


Interactive slicers were added for:

Appointment Type

Age Group

Reminder Sent


Conditional formatting and contrasting colors were also applied to improve interpretation of higher- and lower-risk patterns.


---

🤝 Cross-Track Integration

The Analytics & Insights track contributed validated analytical evidence to the Data Science track.

Potential predictors and relationships provided for further investigation include:

Previous no-show history

Booking lead time

Reminder status

Appointment type combined with previous no-show history


These findings can support feature selection and investigation of interaction effects when developing a patient no-show risk model.


---

💡 Business Recommendations

Based on the analysis, HealthConnect should consider:

1. Prioritizing patients with previous no-shows for additional attendance-support interventions.


2. Strengthening reminder strategies, particularly for appointments with longer booking lead times.


3. Monitoring long-lead appointments, especially those scheduled 31–60 days in advance.


4. Investigating appointment-type differences when designing targeted interventions.


5. Using these validated patterns as inputs for the development and testing of a patient no-show risk model.




---

⚠️ Limitations

The analysis identifies associations and does not establish causation.

Reminder status does not confirm whether a patient received, read, or acted on a reminder.

The dataset may not contain all factors influencing appointment attendance.

Some segments, particularly those with very small numbers of previous no-shows, should be interpreted cautiously.

Further testing and validation are required before using the findings operationally.



---

🚀 Week 7 Focus

The next stage will focus on testing, refinement, and end-to-end validation of the analytical outputs and their integration with the wider HealthConnect solution.


---

👤 Contribution

Role: Analytics & Insights

This contribution focused on advanced analysis, KPI validation, Power BI reporting, evidence-based insights, business recommendations, and providing analytical inputs to support the Data Science track.
