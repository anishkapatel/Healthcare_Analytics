# Healthcare Operations & Revenue Analytics

## Overview

This project presents an end-to-end healthcare analytics workflow that transforms raw clinical and operational data into actionable business insights. Python was used for ETL, exploratory data analysis (EDA), data transformation, feature engineering, and statistical visualization, while Power BI was used to develop an interactive dashboard for monitoring hospital performance.

The project integrates multiple clinical and operational datasets into a star-schema data model, enabling efficient analysis of patient encounters, disease patterns, treatment utilization, resource allocation, and hospital revenue.

---

## Project Objectives

The objective of this project was to build a scalable healthcare analytics solution capable of supporting operational and financial decision-making. The workflow focuses on preparing healthcare data for analysis, deriving meaningful patient metrics, identifying trends through exploratory analysis, and developing an interactive dashboard to monitor key performance indicators.

---

## Dataset Structure

The project processes more than **25 relational tables** organized into fact, dimension, and bridge tables following a star-schema architecture.

The primary fact tables include:

- FactEncounter
- FactTreatment
- FactCost
- FactVitals
- FactLabTests
- FactSpecialTests
- FactTreatmentCost

Supporting dimension tables contain patient demographics, disease information, physician details, insurance plans, room information, treatment details, and date attributes. Bridge tables model many-to-many relationships between encounters, healthcare providers, chronic diseases, allergies, and additional hospital services.

---

## Methodology

### ETL & Data Preparation

Healthcare datasets were imported into Python and prepared through an ETL workflow that included duplicate removal, missing value treatment, datatype conversion, column standardization, and validation checks. The cleaned datasets were exported for downstream analysis and dashboard development.

### Data Transformation

Several analytical healthcare metrics were derived to enhance reporting capabilities. These included patient age, Body Mass Index (BMI), BMI category, length of stay, stay category, radiology and endoscopy indicators, and additional utilization flags for patient segmentation and operational analysis.

### Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand patient demographics, disease prevalence, treatment utilization, revenue distribution, resource allocation, and operational performance. These findings guided KPI selection and dashboard design.

### Data Visualization

Python libraries including **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** were used to develop analytical visualizations for revenue trends, disease distributions, patient segmentation, cost breakdowns, Pareto analysis, treatment utilization, correlation analysis, and operational performance.

### Dashboard Development

The processed datasets were imported into **Power BI**, where an interactive dashboard was developed to monitor hospital revenue, patient encounters, disease trends, operational KPIs, treatment utilization, and resource allocation using interactive filters and drill-down capabilities.

---

## Business Insights

The analysis identified key revenue drivers, disease prevalence patterns, treatment utilization trends, patient segmentation characteristics, resource allocation patterns, and length-of-stay distributions. These insights support data-driven decision-making while highlighting opportunities for operational improvement and cost optimization.

---

## Technologies Used

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| Python Libraries | Pandas, NumPy, Matplotlib, Seaborn |
| Dashboarding | Power BI |
| Development Environment | Google Colab |

---

## Project Highlights

- Processed and analyzed **25+ relational healthcare tables**.
- Performed **ETL and exploratory data analysis (EDA)** using Python.
- Integrated clinical datasets into a **star-schema data model**.
- Created **8+ derived healthcare metrics** for patient and operational analysis.
- Developed **15+ analytical visualizations** using Python.
- Built an interactive **Power BI dashboard** for healthcare operations and revenue analysis.

---

## Repository Structure

```text
Healthcare-Operations-Revenue-Analytics/
│
├── Data/
│   ├── Raw_Data/
│   └── Cleaned_Data/
│
├── Python/
│   ├── Data_Cleaning.ipynb
│   ├── Derived_Metrics.ipynb
│   ├── EDA.ipynb
│   └── Business_Visualizations.ipynb
│
├── PowerBI/
│   └── Healthcare_Operations_Analytics.pbix
│
├── Images/
│   ├── Dashboard.png
│   └── Visualizations/
│
└── README.md
```

---

## Dashboard Preview

Add screenshots of the Power BI dashboard and key Python visualizations in this section.

---

## Skills Demonstrated

- ETL
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Transformation
- Feature Engineering
- Data Modeling
- Star Schema Design
- Healthcare Analytics
- Data Visualization
- KPI Development
- Business Intelligence
- Power BI Dashboard Development
- Python (Pandas, NumPy, Matplotlib, Seaborn)

---

## Dataset Attribution

This project is built using the **MedSynora DW (Data Warehouse)** dataset for educational and analytical purposes. The dataset models patient demographics, encounters, diagnoses, treatments, laboratory investigations, vital signs, insurance details, room allocation, and healthcare costs using a data warehouse architecture comprising fact, dimension, and bridge tables.

The repository focuses on the ETL workflow, exploratory data analysis (EDA), feature engineering, Python visualizations, and Power BI dashboard development performed on the dataset. Please refer to the original dataset documentation and license for attribution and usage terms.
