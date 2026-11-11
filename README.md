🏥 Axon Medical Analytics

Power BI dashboard on 10,000+ patient records to understand patient demand, revenue sources and follow-up performance.

 Business Problem
How can the hospital improve patient follow-ups and understand which departments and treatments drive patient volume and revenue?

 Dataset
- 10,000 patients, 10,000 visits, 1,000 doctors
- Key fields: age, gender, diagnosis, treatment type, department, state, visit date, treatment cost, lab results, follow-up status

 Tools
SQL  • Power Query • Power BI (DAX) • Excel

 Approach
1. Cleaned and validated the data using SQL, Pandas and Power Query
2. Built a data model and DAX measures for revenue, follow-up rate and lab results
3. Designed an interactive dashboard with filters for gender, treatment type, diagnosis, state and visit date

 Key Metrics
| Metric | Value |
|---|---|
| Total patients | 10K |
| Total revenue | $25.4M |
| Average treatment cost per visit | $524.7 |
| Average patient age | 49 |
| Follow-up rate | 49.84% |
| Abnormal lab results | 33.5% |

 Key Findings
- Only about half of patients (49.84%) had a follow-up, so follow-up is a clear area to improve
- Revenue is spread evenly across treatment types (Vaccination $6.6M, Surgery $6.4M, Medication $6.2M, Physical Therapy $6.2M), so no single service drives income
- General Medicine (2,170), Pediatrics (2,092) and Cardiology (2,068) had the most patients
- About one in three lab results (33.5%) was abnormal
- Visits peaked in August and October and were lowest in April

 Recommendations
- Plan staffing around the seasonal visit pattern
- Set up a follow-up reminder process to improve patient retention

 Dashboard Preview
![Axon Dashboard](images/axon-powerbi.png)

 Repository Contents
- `sql/` – analysis queries
- `dashboards/` – Power BI file
- `images/` – screenshots

 Contact
[LinkedIn](https://www.linkedin.com/in/haripriyakt) • haripriyakt33@gmail.com
