# HCDataSet-Tableau

Project Overview
This project analyzes healthcare data from the HCDataSet (Kaggle) to identify key performance indicators and trends in hospital operations. The analysis focuses on readmission rates, length of stay, emergency department throughput, mortality rates, ambulatory visits, and blood pressure control metrics.

1.Hospital Readmission Rate Analysis

<img width="600" height="500" alt="Screenshot 2025-11-05 183450" src="https://github.com/user-attachments/assets/07c88749-ba86-4a6b-8594-57e8f6bb5734" />

•	Overall Readmission Rate: 26.94%
•	Identifies high-risk patient populations (Stroke: 72.22%, Heart Failure: 54.88%)
•	Analyzes weekly trends and demographic patterns
•	Provides insights for targeted intervention programs


2.Emergency Department (ED) Throughput Analysis

<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/08ac4ca2-a573-4d1b-8972-a390bd82acec" />

Key Performance Indicators:
•	Median ED Throughput Time: 11.67 hours
•	Total ED Visits: Approximately 1,200+ visits analyzed

Daily Trends (January 2020):
•	Shortest Throughput: January 7 with optimal patient flow
•	Highest Discharge Volume: January 8 (despite longer throughput times)
•	Variable throughput times ranging from 8.9 to 14.8 hours

Visit Acuity Analysis:
•	Acuity Level 5: Highest admission count (179 patients) - critical conditions
•	Acuity levels range from 1 (mild) to 5 (critical)
•	Higher acuity levels correlate with increased admission rates
Top Reasons for ED Visits:
1.	Fever: 234 visits (median throughput: 11.99 hours)
2.	Stomach Ache: 186 visits (median throughput: 10.97 hours)
3.	Pneumonia: 201 visits (median throughput: 11.24 hours)
4.	Shortness of Breath: 149 visits (median throughput: 12.29 hours)
5.	Chest Pain: 109 visits (median throughput: 11.91 hours)
Disposition Patterns:
The ED disposition shows a balance between admitted and discharged patients, with variations based on acuity levels and visit reasons.


3. Mortality Rate Analysis
<img width="600" height="500" alt="Screenshot 2025-11-05 142922" src="https://github.com/user-attachments/assets/cc5c4408-0936-4278-af0a-ddb13a8c4b97" />

Key Findings:
•	Overall Mortality Rate (O:E Ratio): 0.43 
o	Actual mortality is consistently lower than expected, indicating quality care delivery
Monthly Mortality Trends:
•	January: 38 observed vs 94.45 expected deaths
•	February: 59 observed vs 121.53 expected deaths (highest actual count)
•	March: 7 observed vs 27.43 expected deaths
Insight: The hospital is performing significantly better than expected mortality benchmarks, particularly in February where actual deaths were lower despite being the highest observed count.
Mortality by Diagnosis:
Highest Observed Mortality:
1.	Heart Failure: 16 deaths
2.	Pneumonia: 16 deaths
3.	Hypertension: 16 deaths
4.	Flu: 11 deaths
Demographic Analysis:
•	Highest Mortality Group: Male, English-speaking, Black/African-American patients (39 deaths)
•	Second Highest: Female, English-speaking, White patients (19 deaths)
•	Gender and language appear to influence mortality outcomes, requiring further investigation

   
5. Ambulatory Visits Analysis

<img width="600" height="500" alt="Screenshot 2025-11-05 143115" src="https://github.com/user-attachments/assets/e3b08d01-09f0-4efd-9d71-60fb3fd7ffeb" />

Key Performance Indicators:
•	No Show Rate: 16.21% (average)
•	Average Wait Time: 16 days
•	New Visit Count: 120 patients
•	Completed Visit Status: 736 visits

Visit Type Distribution:
•	Follow Up: 266 completed visits (highest)
•	New Visits: 120 patients
•	Physical Exams: Significant volume
•	Telemedicine: Growing utilization

Weekly Trends:

Average Wait Time by Visit Type:
•	Consistent wait times ranging from 30-70 days across different visit types
•	Week 9 showed the highest combined wait time at 70+ days
•	Follow-up visits showed the most consistent completion rates

No Show Trends:
•	Peak No Show Rate: Week 10 at 40.6%
•	Lowest No Show Rate: Week 6 at 2.9%
•	Average fluctuation suggests need for appointment reminder systems
•	The trend indicates a correlation between longer wait times and higher no-show rates

Completed Visits Weekly Trend:
•	Physical visits peaked in Week 15 (31 visits)
•	Follow-up visits remained consistently high across weeks
•	Telemedicine visits showed steady adoption in later weeks


Live Dashboard
https://public.tableau.com/app/profile/preetha.m7646/viz/AnalysisHealthcareData/HCDataAnalysis


