# Hospital Readmission Risk & Financial Impact Analysis

## Project Overview

Hospital readmissions significantly increase healthcare costs and indicate potential gaps in patient care quality. This project analyzes hospital patient data to identify high-risk patient groups and estimate financial savings achievable through targeted intervention strategies.

The project combines **Python data analysis** with an **interactive Tableau dashboard** to support data-driven decision making for healthcare administrators.

---

## Business Problem

Unplanned 30-day readmissions increase hospital operational costs, reduce efficiency, and impact patient outcomes. Hospitals need the ability to identify high-risk patients early and evaluate whether intervention programs justify the investment.

---

## Objectives

- Identify patients at high risk of readmission  
- Analyze readmission patterns across demographics and visit history  
- Estimate financial impact under different intervention scenarios  
- Build an executive decision-support dashboard  

---

## Dataset

- 100k+ hospital patient records  
- Inpatient visits, emergency visits, demographics  
- Readmission indicators  
- Financial simulation data for ROI estimation  

**Source:** Kaggle Healthcare Dataset

---

## Key Insights

- Patients with more than **10 inpatient visits** show the highest readmission risk (~58%)  
- Prior emergency visits strongly correlate with readmission probability  
- High-risk patients represent the largest opportunity for intervention impact  
- A **30% reduction scenario** could save approximately **$7.16M annually**  

---

## Financial Impact Simulation

Savings scenarios evaluated:

- 10% reduction  
- 20% reduction  
- 30% reduction  

Financial metrics calculated:

- Total Savings  
- Intervention Cost  
- Net ROI  
- Savings per High-Risk Patient  

---

## Tools & Technologies

- Python (Pandas, NumPy)  
- Data Visualization (Matplotlib, Seaborn)  
- Tableau (Dashboard Development)  
- Data Cleaning & Feature Engineering  
- Exploratory Data Analysis (EDA)  

---

## Project Workflow

Data → Python Cleaning → Feature Engineering → EDA → Financial Modeling → Tableau Dashboard → Business Insights  

### 1. Data Collection
- Dataset downloaded from Kaggle containing hospital patient records.

### 2. Data Cleaning & Preprocessing
Performed using Python (Google Colab):

- Handled missing values  
- Corrected data types  
- Removed inconsistencies  
- Prepared features for analysis  

### 3. Exploratory Data Analysis (EDA)

Analyzed relationships between:

- Inpatient visits  
- Emergency visits  
- Demographics  
- Length of stay  
- Readmission outcomes  

Identified strong utilization-based risk drivers.

### 4. Feature Engineering & Risk Segmentation

Created:

- Inpatient visit buckets  
- Emergency visit buckets  
- High-risk patient flag  
- Risk segmentation metrics  

Enabled targeted intervention analysis.

### 5. Financial Impact Modeling

Estimated potential savings using:

- Average cost per readmission  
- Intervention cost assumptions  
- Reduction scenarios (10%, 20%, 30%)  

Calculated ROI and cost-benefit metrics.

### 6. Dashboard Development

Built an interactive Tableau dashboard for executive-level decision support.

Dashboard includes:

#### KPIs
- Total Patients  
- Readmission Rate  
- High-Risk Patients  
- Potential Savings  

#### Visual Analytics
- Readmission drivers by visit frequency  
- Demographic analysis  
- Financial impact comparison  

#### Interactive Features
- Scenario selector (10% / 20% / 30%)  
- High-risk patient filtering  
- Dynamic financial insights  

---

## Dashboard Preview

![Dashboard Screenshot](https://github.com/user-attachments/assets/7936d200-e567-4a46-a77a-1556eb01d5df)

---
---

## Live Dashboard

Explore the interactive Tableau dashboard:

🔗 **Tableau Public:**  
https://public.tableau.com/views/Hospital_Readmission_Dashboard_Portfolio/HospitalReadmissionDashboard

The dashboard provides dynamic filtering, financial scenario analysis, and risk segmentation insights for healthcare decision-making.

---
## Repository Structure

```
hospital-readmission-analysis/
│
├── data/
│   ├── diabetic_raw_data.csv
│   ├── hospital_cleaned.csv
│   ├── roi_data.csv
│   └── savings_per_patient.csv
│
├── dashboard/
│   └── Hospital_Readmission_Dashboard.twbx
│
├── notebooks/
│   └── Hospital_readmission_analysis.ipynb
│
└── README.md
```
The project workflow follows a structured pipeline from raw data ingestion to cleaned datasets, analytical modeling, and final dashboard visualization.
---

## How to Run

1. Clone the repository
2. Open the notebook in Jupyter or Google Colab
3. Ensure dataset files are placed in the `data` folder
4. Run the notebook cells sequentially
5. Open Tableau dashboard file to explore visualization

---

## Business Impact

This project demonstrates how hospitals can:

- Prioritize interventions for high-risk patient groups  
- Optimize resource allocation  
- Estimate ROI before implementing programs  
- Reduce avoidable readmission costs  

The dashboard supports **data-driven healthcare decision making**.

---

## Author

**Jai Siddharth**  
Aspiring Data Analyst
