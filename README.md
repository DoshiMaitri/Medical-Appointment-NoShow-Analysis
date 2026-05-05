# Medical Appointment No-Show Analysis

## Problem Statement
In healthcare systems, patient no-shows lead to wasted resources, increased costs, 
and reduced quality of care. This project analyzes 110,000+ medical appointment 
records to identify key factors driving patient no-shows and build a predictive model 
to flag high-risk appointments.

## Dataset
- **Source:** Brazilian public health system (Kaggle)
- **Size:** 110,527 records
- **Features:** Patient demographics, medical conditions, scheduling details, 
  SMS reminders, and appointment outcomes

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Key Findings
- Patients with **longer waiting times (7+ days)** are significantly more likely 
  to miss their appointments
- **SMS reminders** show a counterintuitive pattern — patients who received SMS 
  had a higher no-show rate, suggesting they are sent reactively to already 
  high-risk patients
- Patients with **chronic conditions** (Hypertension, Diabetes) show better 
  attendance, likely due to perceived medical urgency
- **Same-day appointments** have the lowest no-show rate across all groups
- Female patients make up ~65% of appointments but no-show rates are 
  similar across genders

## Recommendations
- Reduce scheduling wait times — keep under 7 days for non-critical appointments
- Redesign SMS reminder strategy — send earlier and to a broader patient base
- Prioritize follow-up calls for patients with long waiting times and no 
  chronic conditions

## How to Run
1. Clone the repository
```bash
   git clone https://github.com/DoshiMaitri/Medical-Appointment-NoShow-Analysis.git
```
2. Install dependencies
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
```
3. Open the notebook
```bash
   jupyter notebook Medical_Appointments_Data_EDA.ipynb
```

## Author
**Maitri Doshi**  
BTech in Artificial Intelligence and Machine Learning  
[LinkedIn](https://linkedin.com/in/maitri-doshi-a59045245) | 
[GitHub](https://github.com/DoshiMaitri)