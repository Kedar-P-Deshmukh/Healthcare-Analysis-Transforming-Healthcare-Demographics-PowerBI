# Healthcare-Analysis-Transforming-Healthcare-Demographics-PowerBI

**Problem Statement:-**
This project’s  objective is to leverage Power BI for a deep dive into the provided healthcare datasets. This task encompasses meticulous data cleaning and sophisticated data modelling, utilizing DAX for advanced analytics. Our goal is to create a comprehensive, interactive dashboard in Power BI that presents a cohesive narrative of the healthcare data. This dashboard should serve as a tool to uncover and visualize important trends, such as the interplay between patient demographics and treatment outcomes, cost implications of various medical procedures, and overall hospital performance metrics. This analysis will provide invaluable insights, aiding healthcare providers in enhancing patient care and operational efficiency, and positioning HealthStat Solutions at the forefront of healthcare analytics.


**Data Source:-**
HealthcareDataset1.xlsx
The "HealthcareDataset1.xlsx" file contains the following columns:
1.	PatientID: A unique identifier for each patient. (Primary Key)
2.	PatientName: Name of the patient.
3.	Age: Age of the patient.
4.	Gender: Gender of the patient.
5.	BloodType: Blood type of the patient.
6.	Diagnosis: The diagnosis given to the patient.
7.	Treatment: The treatment provided to the patient.
8.	AdmissionDate: Date when the patient was admitted.
9.	DischargeDate: Date when the patient was discharged.
10.	TotalBill: The total bill amount for the patient's treatment.
11.	Full Prescription Details: Detailed prescription information including medication names, dosages, frequency, and duration

The "HealthcareDataset2.xlsx" file contains the following columns:
1.	PatientID: A unique identifier for each patient, corresponding to 'PatientID' in "HealthcareDataset1.xlsx". (Foreign Key)
2.	Hospital: The name of the hospital where the patient was treated.
3.	DoctorName: Name of the doctor who treated the patient.
4.	RoomNumber: The room number assigned to the patient.
5.	DailyCost: The daily cost of the patient's treatment.
6.	TreatmentType: Type of treatment provided.
7.	RecoveryRating: A rating of the patient's recovery (out of 10).

**Approach:-**
Part 1: Data Cleaning, Modeling, and DAX in Power BI
1.	Data Importing and Initial Examination 
o	Imported both datasets into Power BI. Performed a preliminary examination of the data. Identified any data quality issues or inconsistencies.
2.	Merging and Relating Datasets 
o	Merged the datasets using a suitable column as a key. Ensured that the merge is accurate and retains all necessary information.
3.	Cleaning: Handling Missing and Irrelevant Data 
o	Identified and addressed missing data in both datasets. Addressed duplicate entries and irrelevant data points, ensuring data quality.
4.	Data Type Conversion 
o	Converted 'AdmissionDate' and 'DischargeDate' to the appropriate date formats. Calculate the length of stay for each patient.
5.	New column creation

o	Created a new column categorizing patients into age groups (e.g., Child, Adult, Senior). 
o	Calculate the total cost of treatment for each patient 
6.	Chart preparations: -
o	Prepared various chart and graphs to find insights of data
Part 2: Dashboard Building
1.	Comprehensive Healthcare Dashboard 
o	Created a dashboard in Power BI showcasing key metrics like patient demographics, diagnosis distribution, treatment costs, and recovery ratings. Include filters for hospitals, diagnosis, and treatment types.
2.	Interactive Hospital Performance Comparison 
o	Create an interactive section comparing different hospitals' performance based on patient load, treatment costs, and recovery ratings.

 ![Alt text]([image_url](https://drive.google.com/file/d/1xrQwlxjijoKTuT83LzffD-tdrLzywOJo/view?usp=sharing))

 ![Alt text]([image_url](https://drive.google.com/file/d/1EKm_a1HQsNBpG_uBzWZUBdYpVn7BElpy/view?usp=sharing))


**Key Insights :-**
Higher number of patients lead to lower average recovery rating for a doctor.   
Average recovery rating for counselling was highest with 5.58 and for surgery it was least with 5.24.   
Average room utilization of room is hospital is around 1.2 with Green Valley Medical Center has highest average room utilisation of 1.26 on the country maple grow health facility has the list average room utility of 1.14.   
Higher number of patients lead to lower average recovery rating for a doctor.   
Cedar Sinai Clinic has the highest average total cost followed by Green Valley Medical Centre, maple grow health facility silver Oak medical plaza and riverside hospital.   

There was serge in average total cost in 2022.   

**Conclusion: -**
In this project we analysed healthcare datasets using Power BI. We pre-processed the data by cleaning and mean amputation, created new columns,
Drew various charts to find insight and created dashboards to effectively visualize data.
This will help hospital and related entities to improved patient outcomes and optimized hospital operations.
