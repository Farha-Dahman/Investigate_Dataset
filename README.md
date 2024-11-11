# No-show Appointments Data Analysis

## Project Overview
This project investigates factors influencing patient no-shows for medical appointments using the [Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments) dataset. The analysis focuses on identifying trends and associations related to no-show rates, which can provide insights for healthcare providers to improve appointment attendance.

## Dataset Description
The dataset used in this analysis contains information about 110,527 medical appointments in Brazil. Each record in the dataset represents a single appointment, including details about the patient and the appointment itself. The goal is to determine what factors are associated with whether or not a patient shows up for their appointment.

## Key Variables
- **PatientID:** Unique identifier for each patient.
- **AppointmentID:** Unique identifier for each appointment.
- **Gender:** Gender of the patient.
- **ScheduledDay:** The day the patient scheduled the appointment.
- **AppointmentDay:** The actual day of the appointment.
- **Age:** Age of the patient.
- **Neighbourhood:** The location of the appointment.
- **Scholarship:** Indicates if the patient is enrolled in the Bolsa Família program (a social welfare program).
- **Hipertension:** Indicates if the patient has hypertension.
- **Diabetes:** Indicates if the patient has diabetes.
- **Alcoholism:** Indicates if the patient has a history of alcoholism.
- **Handcap:** Indicates if the patient has any disability.
- **SMS_received:** Indicates if the patient received an SMS reminder.
- **No-show:** Indicates if the patient did not show up for the appointment. ("Yes" means they did not show up; "No" means they did.)


## Research Questions
The primary research questions explored in this project include:

- Does receiving an SMS reminder influence no-show rates?
- What factors are associated with higher no-show rates?
- How do no-show rates vary by neighborhood?
- Is there a relationship between age and no-show rates?
- Does having a scholarship affect showing up to an appointment?
- Is there a relationship between gender and no-show rates?


## Project Structure
- ***Data Wrangling:*** Loaded and cleaned the data, including handling missing values, correcting data types, and transforming columns where necessary.

- ***Exploratory Data Analysis (EDA):*** Visualized trends and distributions related to no-show rates, analyzed relationships between variables, and conducted basic statistical tests.

- ***Conclusions:*** Summarized key findings from the EDA and outlined potential factors influencing no-show rates. Also noted limitations and provided suggestions for further investigation.

### Libraries Used
- Pandas: For data manipulation and cleaning.
- NumPy: For numerical operations.
- Matplotlib and Seaborn: For data visualization.

### Limitations and Further Research
- Data Limitation: The dataset only includes appointments from Brazil, which may limit the generalizability of the findings.
- Further Research: Additional data, such as transportation availability or weather conditions, could help provide a more comprehensive view of factors affecting no-show rates.

### Conclusion
This project provided insights into factors affecting no-show rates in medical appointments. Understanding these factors can help healthcare providers take actionable steps to improve attendance rates, potentially by targeting specific patient groups with reminders or other interventions.