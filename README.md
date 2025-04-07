🔍 Project Overview

This project explores and analyzes a dataset of over 110,527 medical appointments to understand why patients fail to show up for their scheduled appointments. The primary goal is to perform thorough data cleaning, insightful EDA for their appointment.

📅 Dataset Description

The dataset contains the following columns:

PatientId: Unique identifier for the patient

AppointmentID: Unique identifier for each appointment

Gender: Male or Female

ScheduledDay: The day the appointment was scheduled

AppointmentDay: The day of the actual appointment

Age: Age of the patient

Neighbourhood: Location of the hospital

Scholarship: 1 if enrolled in welfare program, 0 otherwise

Hipertension: 1 if the patient has hypertension

Diabetes: 1 if the patient has diabetes

Alcoholism: 1 if the patient is alcoholic

Handcap: Number of disabilities

SMS_received: 1 if the patient received an SMS reminder

No-show: 'Yes' if the patient missed the appointment, 'No' otherwise (Target Variable)

🪑 Data Cleaning Steps

Removed invalid data (e.g., negative ages)

Dropped non-informative identifiers (PatientId, AppointmentID)

Renamed columns for clarity (e.g., Hipertension → hypertension)

Converted ScheduledDay and AppointmentDay to datetime format

Encoded target variable: No-show: 'Yes' → 1, 'No' → 0

📊 Exploratory Data Analysis

Analyzed distributions of age, gender

Visualized no-show ratios by different features using:

Countplots

Histograms

Correlation heatmaps

Identified important factors such as age,gender and SMS reminders
