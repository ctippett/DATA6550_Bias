# DATA6550_Bias (group 5)
This GitHub repo is for our group project in module 2.  
Authors: Miracle Awonuga, Stiven LaVrenov, Abigail Roberts, and Charles Tippett

## Dataset
Our dataset is diabetes_data.csv in the Data folder. The different data values can be found below. The dataset comes from the class DATA 6500 from Fall of 2024, taught by Dr. Liu.

1. encounter id: Integer unique identifier of an encounter.
2. patient nbr: Integer unique identifier of a patient.
3. race: Race of the patient, represented as a string (e.g., Caucasian, African American).
4. gender: Gender of the patient, represented as a string (e.g., Male, Female).
5. admission type id: Categorical ID representing the type of admission (e.g., emergency, urgent,
elective) as a string.
6. discharge disposition id: Categorical ID indicating the disposition of the patient at discharge
(e.g., discharged to home, transferred to another medical facility) as a string.
7. admission source id: Categorical ID indicating the source of the hospital admission (e.g.,
emergency room, physician referral) as a string.
8. time in hospital: Integer number of days the patient stayed in the hospital.
9. num lab procedures: Integer number of lab tests performed during the encounter
10. num procedures: Integer number of medical procedures (other than lab tests) performed
during the encounter.
11. num medications: Integer number of distinct medications prescribed during the encounter.
12. number outpatient: Integer number of outpatient visits by the patient in the year preceding
the encounter.
13. number emergency: Integer number of emergency visits by the patient in the year preceding
the encounter.
14. number inpatient: Integer number of inpatient visits by the patient in the year preceding the
encounter.
15. diag 1: Primary diagnosis coded as an ICD-9 code.
16. diag 2: Secondary diagnosis coded as an ICD-9 code.
17. diag 3: Additional secondary diagnosis coded as an ICD-9 code.
18. number diagnoses: Integer number of diagnoses entered in the system for the encounter.
19. max glu serum: Maximum glucose serum test result during the encounter (e.g., None, Norm,
>200, >300).
20. A1Cresult: Result of the A1C test (e.g., None, Norm,>7, >8).
21. metformin: Status of Metformin medication (e.g., No, Up, Down, Steady).
22. repaglinide, nateglinide, chlorpropamide, glimepiride, acetohexamide, glipizide, glyburide, tolbutamide, pioglitazone, rosiglitazone, acarbose, miglitol, troglitazone, tolazamide, examide, citoglipton, insulin, glyburide-metformin, glipizide-metformin,
glimepiride-pioglitazone, metformin-rosiglitazone, metformin-pioglitazone: Status of
each medication (e.g., No, Up, Down, Steady).
23. change: Indicates if there was any change in diabetic medications (Change/No Change).
24. diabetesMed: Indicates if any diabetes medication was prescribed (Yes/No).
25. readmitted: Category of readmission (e.g., <30, >30, No).
26. age catg: Categorized age of the patient, represented as a category (likely coded into categories
such as 1[0 − 60), 1.5[60 − 80) and 2[80 − 100) ).


## Report
Our final report on the potential biases found in this dataset may be found at the Google Doc linked below.  
https://docs.google.com/document/d/1WzbesJ_1BYXMi9-HqjEdWUkySQhzTrQXOLAOcwG6nrs/edit?tab=t.0 
