# No-Show Appointments Exploratory Data Analysis (EDA)

This project explores a medical appointments dataset to investigate the factors influencing whether patients show up for their scheduled appointments.

## Dataset Overview
The dataset contains information about medical appointments in Brazil, focusing on variables such as patient demographics, neighborhood locations, scholarship enrollment (Bolsa Família), SMS reminders, and whether the patient showed up.

## Key Steps & Methodology
- **Data Wrangling & Cleaning:** Inspected missing values, corrected data types (such as converting dates), cleaned column names, and checked for logical errors (e.g., negative ages).
- **Exploratory Data Analysis (EDA):** Grouped and aggregated data to uncover patterns related to age, gender, geographic location, and SMS notification impact.
- **Reusable Functions:** Implemented modular functions for consistent plot formatting and styling.

## Key Findings
- **Age Impact:** Younger age groups (especially patients under 20) exhibited higher no-show rates.
- **Gender Independence:** Gender showed no significant difference, with both male and female patients showing roughly identical attendance rates (~20% no-show).
- **Geographical Factors:** Certain neighborhoods experienced higher missed appointment rates, indicating potential access or logistical barriers.
- **SMS Reminders:** Counter-intuitively, patients who received SMS reminders had higher no-show rates, suggesting reminders are predominantly targeted at higher-risk or chronically absent patients.

## Technologies Used
- Python
- Pandas & NumPy (Data manipulation)
- Matplotlib & Seaborn (Data visualization)
- Jupyter Notebook / Google Colab

