# Hospital Readmission Risk Analysis

## Project Overview
This project analyzes hospital encounter data to identify patterns associated with **30-day hospital readmission**.

The project follows an end-to-end data analysis workflow covering data understanding, profiling, quality assessment, cleaning, exploratory analysis, visualization, recommendations, and dashboard development.

**Primary Tool:** Microsoft Excel 2016

## Objectives
- Understand the structure and characteristics of the dataset.
- Create a comprehensive data dictionary.
- Profile and assess data quality.
- Clean and prepare the dataset for analysis.
- Analyze factors associated with 30-day readmission.
- Create meaningful visualizations.
- Identify important readmission patterns.
- Develop practical recommendations.
- Build a final Excel dashboard.
- Document the complete analytical workflow.

## Dataset
The dataset contains hospital encounter information covering patient demographics, healthcare utilization, hospitalization characteristics, and clinical variables.

### Key Areas Analyzed
- Patient demographics
- Previous inpatient visits
- Previous emergency visits
- Admission type and source
- Discharge disposition
- Length of stay
- Number of diagnoses
- Number of medications
- A1C and glucose-related indicators
- 30-day readmission status

The primary outcome of interest is **30-day hospital readmission**.

> **Note:** The original patient-level dataset is not included unless it is confirmed to be publicly shareable and appropriately anonymized.

## Project Workflow

### 1. Data Understanding
- Reviewed dataset structure.
- Identified variables and their meanings.
- Created a data dictionary.

### 2. Data Profiling
- Checked data types.
- Examined missing values.
- Analyzed duplicate values.
- Reviewed unique values.
- Profiled categorical variables.
- Analyzed numerical distributions.

### 3. Data Quality Assessment
- Evaluated completeness.
- Checked uniqueness.
- Reviewed categorical consistency.
- Investigated unusual and unknown values.
- Validated identifier fields.

### 4. Data Cleaning
- Reviewed missing and unknown values.
- Checked duplicate records.
- Validated identifier columns.
- Used ID-mapping information where required.
- Reviewed numerical values and distributions.
- Documented cleaning activities in a cleaning log.

### 5. Exploratory Data Analysis
30-day readmission was examined across:
- Age
- Prior inpatient visits
- Prior emergency visits
- Admission type
- Admission source
- Discharge disposition
- Length of stay
- Number of diagnoses
- Number of medications
- A1C result
- Other relevant clinical and utilization variables

### 6. Visualization
The project includes:
- Overall Readmission Distribution
- 30-Day Readmission by Age
- 30-Day Readmission by Prior Inpatient Visits
- 30-Day Readmission by Previous Emergency Visits
- 30-Day Readmission by Discharge Disposition
- 30-Day Readmission by Length of Stay
- 30-Day Readmission by Number of Diagnoses
- 30-Day Readmission by A1C Result
- 30-Day Readmission by Number of Medications
- Top Factors Associated with 30-Day Readmission

### 7. Recommendations
Recommendations were developed from observed patterns, focusing on:
- Post-discharge follow-up
- Transition-of-care planning
- Previous healthcare utilization
- Greater clinical complexity
- Appropriate follow-up for relevant diabetes-related indicators

### 8. Dashboard
The final Excel dashboard summarizes:
- Total Encounters
- 30-Day Readmissions
- Overall 30-Day Readmission Rate
- Readmission patterns
- Top observed factors
- Key findings
- Recommendations

## Key Findings
The exploratory analysis identified differences in observed 30-day readmission rates across demographic, clinical, hospitalization, and healthcare-utilization factors.

Important patterns were examined across:
- Previous inpatient utilization
- Previous emergency utilization
- Age groups
- Length of stay
- Discharge disposition
- Number of diagnoses
- Number of medications
- A1C categories

> **Important:** These findings represent observed associations within the dataset and do not establish causation.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel 2016 | Data cleaning, analysis and dashboard development |
| Excel Formulas | Data preparation and calculations |
| Excel PivotTables | Aggregation and comparative analysis |
| Excel Charts | Data visualization |
| CSV Files | Dataset and ID mapping |

## Repository Structure

```text
hospital-readmission-risk-analysis/
│
├── README.md
├── data/
│   └── README.md
├── documentation/
│   ├── Data_Dictionary.xlsx
│   ├── Data_Profiling.xlsx
│   ├── Data_Quality_Assessment.xlsx
│   ├── Data_Cleaning_Log.xlsx
│   └── Project_Report.pdf
├── analysis/
│   └── Hospital_Readmission_Analysis.xlsx
├── dashboard/
│   └── Hospital_Readmission_Dashboard.xlsx
└── screenshots/
    └── dashboard.png
```

The exact files may vary depending on the final project organization.

## Limitations
- The analysis is primarily descriptive and exploratory.
- Observed relationships do not prove causation.
- Some categories may contain relatively small numbers of observations.
- The dataset contains an `Unknown` category for Gender.
- The analysis uses historical hospital encounter data.
- Advanced predictive modeling was not performed.
- Findings should not be used directly for clinical decision-making.

## Future Scope
- Build a machine-learning model for 30-day readmission prediction.
- Perform feature engineering and statistical significance testing.
- Handle class imbalance.
- Compare Logistic Regression, Random Forest, and Gradient Boosting.
- Evaluate models using Precision, Recall, F1-score, ROC-AUC, and PR-AUC.
- Develop an interactive Power BI or Tableau dashboard.
- Validate findings using additional healthcare datasets.

## What I Learned
This project provided practical experience in:
- Data profiling
- Data cleaning
- Data quality assessment
- Data dictionary creation
- Excel formulas
- PivotTables
- Exploratory data analysis
- Data visualization
- Dashboard development
- Healthcare data interpretation
- Translating findings into recommendations
- Documenting an end-to-end data analysis workflow

A key learning was that **data analysis begins with understanding and validating the data before creating visualizations or predictive models**.

## Author
**Manu**  
Student | AI & Data Science Enthusiast

## Disclaimer
This project is intended for **educational and analytical purposes**.

The findings represent observed patterns in the analyzed dataset and should not be interpreted as clinical recommendations or medical advice.
