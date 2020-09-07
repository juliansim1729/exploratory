# Source Info

## cov19_surveillance.csv 
Sourced from https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf on September 1st, 2020. Utilizing public use data from the CDC on the patient-level regarding COVID-19 on the national scale. NAs were coded as 'Missing', with invalid dates being set to null. Additionally, due to the risk of identifying information, low frequency records with a unique combination of demographic characteristics (<5) were suppressed and recoded to NA.

### Codebook (Sourced from CDC)
| Variable Name | Description | Variable Type |
| ------------- | ----------- | ------------- |
| cdc_report_dt | Initial case report date to CDC | Date |
| pos_spec_dt | Date of first positive specimen collection | Date |
| onset_dt | Symptom onset date, if symptomatic | Date |
| current_status | Case status: Lab Confirmed vs Probable | Text |
| sex | Male/Female/Unknown/Other | Text |
| age_group | in groups of ten years | Text |
| race\* | race & ethnicity (combined) | Text |
| hosp_yn | hospitalization status | Text |
| icu_yn | ICU admission status | Text |
| death_yn | Death Status | Text |
| medcond_yn | Present of underlying comorbidity or disease | Text |
\* Was renamed from 'Race and Ethnicity (Combined)' for consistency and coding reasons

