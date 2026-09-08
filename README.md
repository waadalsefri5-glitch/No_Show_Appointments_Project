# No-Show Appointments Exploratory Data Analysis (EDA)

This project explores a medical appointments dataset to investigate factors associated with whether patients show up for their scheduled appointments.

## Dataset Overview
The dataset contains information about medical appointments in Brazil, focusing on variables such as patient demographics, neighborhood locations, scholarship enrollment (Bolsa Família), SMS reminders, and whether the patient showed up.

## Key Steps & Methodology
- **Data Wrangling & Cleaning:** Inspected missing values, corrected data types (such as converting dates), cleaned column names, and checked for logical errors (e.g., negative ages).
- **Exploratory Data Analysis (EDA):** Grouped and aggregated data to uncover patterns related to age, gender, geographic location, and SMS notification status.
- **Reusable Functions:** Implemented modular functions for consistent plot formatting and styling.

## Key Findings
- **Age Impact:** Younger age groups, especially patients under 20, showed higher no-show rates.
- **Gender:** Gender showed little to no noticeable difference, with both male and female patients having roughly similar no-show rates (~20%).
- **Geographical Patterns:** Some neighborhoods showed higher no-show rates than others.
- **SMS Reminders:** Patients who received SMS reminders showed higher no-show rates in this dataset; however, this pattern should be interpreted as an association rather than evidence of causation.

## Technologies Used
- Python
- Pandas & NumPy (Data manipulation)
- Matplotlib & Seaborn (Data visualization)
- Jupyter Notebook / Google Colab
