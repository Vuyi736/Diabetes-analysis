# DIABETES ANALYSIS
Analysis of real DM data across 130 US hospitals for years 1999-2008.

### PROJECT OVERVIEW
The goal of this project is to investigate care of Diabetes patients across 130 hospitals in order to identify patterns in demographics (race, gender, age), quality of care (length of stay, readmission rates, emergencies) and outcomes for the purpose of specializing and improving care, which will also improve outcomes.

### EXECUTIVE SUMMARY
Across 130 hospitals, 9 years' worth of data, a total of 72K patients was cared for. 102K encounters were recorded with an average length of stay (ALOS) of 4.40 days which is within the industry benchmark. A total of 20K emergencies was recorded with 55% being admitted as emergencies. Females constitute more than 50% of the patients that were seen, followed by Males. Caucasians had the most incidences (75%), followed by African Americans(18%) with Asians(1.4%) having the lowest number, suggesting cultural or genetic differences. The age-group most affected is the (70-80) bracket, but, the age group that presented the most emergencies was the (50-60) bracket. Readmission rate in less than <30 days after discharge was 13.19$ which is within the benchmark (14-22%). The mortality rate stood at 2.30% which is slightly above the benchmark (<2%).

 ### KEY METRICS ANALYZED
 - Demographics
   - Race, gender, age
 - Total number of emergencies
 - Total patients
 - Total encounters
 - Average length of stay
 - Readmission rate
 - Mortality rate
   
### RESULTS and INSIGHTS
1. Demographics were as follows:
  - Caucasians constituted 75% of patients, African Americans were 18%, Hispanics at 2.8% and Asians at 1.4%
  - Females constituted 52% while Males came in second at 48%. Similar margins were consistent across races except Asians; where Males were more affected than Females.  
  - The (70-80) age bracket had the most patients (25%) but the (50-60) bracket came in as emergencies the most (5.3%)

 <img width="1320" height="739" alt="Demographics-dm" src="https://github.com/user-attachments/assets/5bf25c79-19fc-47c1-875a-1e12073e66c7" />

2. Totals were as follows:
   - Encounters were 102K
   - Total patients 72k
   - Total emergencies 20K
   - Mortality rate 2.30. This is .30 more higher than the ideal which is <2%.
   - Average length of Stay is 4.40 days which is falls within the benchmark of not keeping patients longer than 7 days
   - Readmission rate (<30 days) was 13.19% which is also within the industry benchmark.
  
 <img width="1216" height="741" alt="QOC-dm" src="https://github.com/user-attachments/assets/469817d9-3dfa-4af7-93cb-8288b6c0bafd" />

     
 The readmission rate was disaggregated against ALOS, number of lab procedures, number of medications, change in dosing, medical specialty and Glycemic control (HbA1C results). These were the results;
  - The longer the stay, the higher the chances of readmission.
  - The more lab procedures and more medications, the higher the chance of readmission. However, there were racial differences.
  - A change in dosing (whether lowering or increasing the dosage) reduced readmissions.
  - Internal medicine was the specialty with the most readmissions.
  - Patients with no results for glycemic control (HbA1C) had the most readmissions which is understandable. This underlines the need to carry out this test in order to choose efficient drugs for patients.
  - More mortalities were evident in patients without the A1C results that measures the efficacy of treatment.
  - The male gender had the most mortalities, while the female gender had the most readmissions. The African Americans had a higher mortality rate than other races. This can be attributed to a longer stay in hospital and the fact that more than 50% did not have HbA1C results.

3. Caucasians had more than 50% of the total emergencies because a large number were admitted as emergencies and more than 50% also did not have HbA1C results.

<img width="1171" height="725" alt="Outcomes-dm" src="https://github.com/user-attachments/assets/2e07092b-156f-47f1-a873-c70a60ec2063" />


### RECOMMENDATIONS
1. To improve Patient outcomes
   - Ensure to check glycemic control after a period of drug administration. Then later change the regimen according to the results.
   - Investigate further why the males have worse outcomes than their counterparts, could it be problems with taking medications on time or correctly? Do they have family to monitor them?
   - Investigate further why African American stay longer in the hospital. Could it be that they wait longer to be seen by health professional?

2. To improve data quality
   - Add timestamp between arriving and being seen by a health professional (waiting time) so that we can investigate from the time angle.
   - Add the years column so that we can investigate from the year point of view. Perhaps the HbA1C test was expensive at the time?
   -  A significant portion of data (weight, race, specialty, etc.) was missing, thus, it could not be established whether they had direct effects on the outcomes and the quality of care. This could be due to data entry errors or data loss. I suggest that training be conducted to improve data quality being entered into the EHR system.

### TOOLS USED
1. Microsoft Excel for initial walkthrough and standardization.
2. Microsoft Power BI for data modelling, Analysis and Visualization.

### LIMITATIONs
- The data did not have timestamps so I could not perform time series analysis.

### REFERENCES
1. Strack, B., Deshazo, J.P., Gennings C., Olmo, J.C., Ventura, S., Cios, K. J. & Clore, J.N. (2014). Impact of HBA1C measurement on hospital readmission rates. Analysis of 70000 clinical database patient records. _Biomed Research International_.Vol2014. Article ID 781670. Retrieved from https://archive.ics.uci.edu/dataset/296/diabetes+130-US+hospitals+for+years+1999-2008.

2. Insightsoftware. (2025). Top 26 healthcare KPIs and quality metric examples for 2026 Reporting._Insightsoftware_. Accessed at Insightsoftware.com 

### DASHBOARD
<img width="1206" height="772" alt="DM Dashboard" src="https://github.com/user-attachments/assets/61c6f242-c164-4e02-aaf2-ee4bd11328bc" />







   
  
