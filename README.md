# Hospital-admissions-and-patients-data-analysis
### PROJECT OVERVIEW
This project explores hospital admission records through Excel-based data analysis. 
With 55,500 entries containing details on patient demographics, medical conditions, admission types, medications, and billing amounts, 
using tools such as PivotTables, charts, and Excel functions, this analysis will produce actionable insights that can aid in clinical and operational decision-making.
### PROBLEM STATEMENT 
Despite abundant healthcare data, hospitals often lack the tools or time to convert raw information into useful insights. 
Understanding the relationships between patient demographics, medical conditions, and treatment costs is essential for enhancing patient outcomes and managing resources. This project uses Excel to analyse a comprehensive hospital dataset to highlight patterns in admissions, costs, and care delivery. 
These insights can guide improvements in both patient services and administrative strategies.
### OBJECTIVES
1. To analyse age distribution and its correlation with medical conditions.  
2. To study gender-specific trends in diagnoses and treatment outcomes.  
3. Investigate the financial impact of medical conditions, focusing on billing amounts.  
4. Evaluate the frequency of admission types (urgent, emergency, elective) by hospital.  
5. Identify common medical conditions and their associated medications.  
6. Assess the influence of blood type on medical conditions and treatments.
7. Analyse the role of insurance providers in covering healthcare costs
### DATA SOURCE 
Kaggle 
### METHODOLOGY
#### TOOL USED: Power Query and Microsoft Excel
#### DATA CLEANING PROCESS AND TRANSFORMATION: 
-	I removed the name column because of the inconsistency 
-	I ensured the datatype of each column is correct, like changing the billing amount from a decimal number datatype to a currency datatype
-	I added an index column and renamed it to Patient ID 
-	I renamed the name1 column to Patient Name 
-	There were no duplicates or errors
-	I capitalised the first letter in the Patient Name column 
-	I loaded the cleaned dataset into Microsoft Excel
### DATA ANALYSIS
Identity trends and patterns in the hospital dataset, from the patient demographic to the billing amount and insurance provider used by the patients 
### KEY INSIGHTS
1.	Demographics and Billing Overview
- Total Patients: 55,500, where 27,774 are males and 27,726 are females
- Average Length of Stay (LOS): 15.5 days, which is long and may point to chronic conditions or a delay in keeping the patients in check. Arthritis is the most reported case across different hospitals, recorded in the dataset
- Average Billing Amount: $25,839 with 5 insurance providers involved 
2.	Medical, Condition vs. Age Group
- Arthritis, Hypertension, and Diabetes are most prevalent in older age groups (53-82) while younger patients (13-32) show fewer cases, likely with more Asthma and Obesity patterns. This suggests age-related chronic disease patterns, common in middle-aged to elderly groups.
3.	Top 10 Hospitals by Admission Type
- These Hospitals have high volumes of patients across all admission types, with variation across different hospitals
4.	Common Medical Conditions & Medications
 - Conditions like Arthritis, cancer and Obesity are associated with high medication use.
- The medication used by patients depends on the type of medical condition. For example, Aspirin is used more than other medications in the treatment of arthritis.
5.	Gender Trend in Diagnoses & Outcomes
- Females show slightly higher diagnoses across most medical conditions (Obesity and Arthritis), while male shows higher diagnoses in medical conditions (Hypertension and Asthma), and it depends on the test outcome.
6.	Medication Usage by Blood Type
- Blood types AB-, AB+, and B+ have the highest prescription counts.
- O- appears to have the lowest medication engagement. Blood type can also determine how patients react to some medical conditions
7.	Financial Impact of Medical Conditions
- Obesity and Diabetes have the highest average billing amounts, suggesting these conditions are most costly.
- Arthritis and Asthma incur lower billing costs, possibly due to outpatient treatment or shorter hospital stays.
8.	Insurance Coverage and Healthcare Costs
- Cigna covers the highest number of patients (11,249) with an average billing of $25,525.
- Medicare covers 11,154 patients, and it has the highest average billing of $25,615.
9.	Condition-wise Insurance Distribution
- Obesity and Diabetes see the highest number of patients across all insurance providers.
- Cancer patients appear fewer in comparison, possibly due to specialised care or referral to specific facilities.
- 
#### RECOMMENDATION 
1.	Prioritise care and preventive screenings for patients aged 50+, focusing on Arthritis, Diabetes, and Hypertension.
2.	Monitor high-demand drugs to prevent stockouts and reduce treatment delays.
3.	Doctors should investigate if blood type correlates with certain condition severity or medication responsiveness. This can guide personalised care plans or genetic studies
4.	Hospital management should strengthen partnerships with Medicare and other major insurers by sharing outcomes data and negotiating better terms for high-cost treatments
5.	Hospital management should prioritise staffing and resources in departments handling high-cost conditions like Diabetes and Obesity
6.	Review and standardise billing processes across insurance types to maintain transparency and accuracy by using the Electronic Health Record (EHR) system.
 ### DASHBOARD 

![Screenshot (147)](https://github.com/user-attachments/assets/40d0dbd2-a9c9-478a-9f35-08efada13cdb)

 ![Screenshot (149)](https://github.com/user-attachments/assets/857ed595-c69b-4ef7-bc0b-07c946ed6b87)
