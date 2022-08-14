# No-Show-Dataset-Project

This is my first project in the Udacity Data Analyst Nanodegree Program.

----
## The Problem Question

>**Question** - What factors are important for us to know in order to predict if a patient will show up for their scheduled 
appointment?

### My Explorative Questions
I compared the absence or presence of patients as a dependent variable to some relevants and insightful independent variables.

**Independent variables**
* Appointment Date convienence
* Gender
* Age
* Hypertension Status
* Neigbhourhood
* Diabetes Status
* Alcoholism Status
* Handicap Status
* SMS reminder

----
## DATA WRANGLING(CLEANING)

**In this section of the report, I loaded my dataset, assessed it and explore it carefully to perform any necessary data cleaning or preparation.**

###  DATA CLEANING
> **1) I have to rename my column titles to be corectly spelt and all in Small letters**

> **2) I have to adjust the wrongly inputted age**

> **3) The Handicap column has 5 different characters but according to the data source it should be 2(1 or 0).**

> **4) Since I don't intend to recognize any patient and there is no duplicate appointment, I can remove both the PatientId and AppointmentID column.**

> **5) The ScheduledDay and the Appointment Day can be used to check if there is a relationship between the proximity of appointment date with responsiveness of patients**

> **6) I will convert the gender and absence status column to boolean for statistical analysis**

> **7) We have 8 independent variables that are of insightful relevance to our analysis**

----
## EXPLORATORY DATA ANALYSIS

> I have cleaned my data, i want to go into deep exploration, compute statistics and create visualizations to address the research questions that i have intriduced earlier.

> I will be performing analysis to detect association and not to imply causation.

> I will be comparing a single dependent Variable which is the presence or absence of the patients on the appointment date with 9 other independent variables.

> These independent variables are in three categories.

**Natural Characteristics of Patients**

*Gender*

*Age*

**Disease Status of Patients**

*Hypertension*

*Diabetes*

*Handicap*

*Alcoholism*

**External factors on Patients**

*Scholarship*

*SMS Recieval*

*Same Day Appointment*

*Neigbhourhood*

----
## CONCLUSIONS

> * The analysis was to know What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment.

> * Generally Older and very young people are more likely to show up for medical appointments while the gender has negligible association with the absence of the patients at appointments.

> * Patients that have hypertension, diabetes and are handicapped are less likely to miss appointment comoared to those who dont have, even though there is a weak correlation but a considerable one enough to suspect an association.

> * There is a negligible association between alcohol taking and presence at medical appointment.

> * Patients that are on scholarship are more likely to miss appointment compared to those who don't have, even though there is a weak correlation but a considerable one enough to suspect an association.

> * Patients that are scheduled on the same date are more likely to miss appointment, it is also important to note that they don't recieve SMS.

----
**LIMITATION**
> * There is no sufficient background knoledge to explore reasons why these neigbhourhood have a lot of missed appointments
