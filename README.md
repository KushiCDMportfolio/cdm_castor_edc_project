# Mock CDM Project: Nipah Virus Infection Observational Study (Castor CDMS)

A self-directed, hands-on Clinical Data Management project built in **Castor CDMS (EDC)**. I designed the study structure and eCRFs, entered fictional participant data, and reviewed the audit trail and study progress dashboard. All data is fictional and created for practice.

## Project overview
- **Study ID:** NIPAH-OBS-001
- **Study type:** Observational (mock) study on Nipah Virus Infection
- **Tool:** Castor CDMS (Electronic Data Capture)
- **Participants:** 10 fictional participants at "Mock Research Centre"
- **Purpose:** To build hands-on EDC experience for an entry-level Clinical Data Management role

## Study structure
6 visits and 14 forms:

| Visit | Forms |
|-------|-------|
| Screening | Informed Consent, Demographics, Medical History |
| Baseline | Clinical Assessment, Laboratory Tests |
| Day 3 | Clinical Assessment, Medication |
| Day 7 | Clinical Assessment, Laboratory Tests, Adverse Events |
| Day 14 | [add the 3 forms from your Day 14 visit] |
| End of study | Final Assessment |

## What I built
- Designed eCRFs with clearly named variables (for example `consent_date`, `body_temperature`, `ae_term`, `ae_outcome`)
- Used different field types: radio buttons, date, number, text, multiline text and dropdown
- Marked key fields as required
- Added units to numeric fields (degree celsius, bpm)
- Entered data for 10 fictional participants across all visits
- Locked completed participant records
- Reviewed the audit trail (721 logged entries) and the study progress dashboard (100% visit completion at the mock site)

## Example forms
| Form | Examples of fields |
|------|--------------------|
| Informed Consent | Consent Obtained, Consent Date, Person Obtaining Consent, Protocol Version |
| Demographics | Subject ID, Age, Sex, Date of Birth, Height, Weight, Ethnicity, Country |
| Medical History | Diabetes, Hypertension, Asthma, Previous Hospitalization, Allergies |
| Clinical Assessment | Fever, Body Temperature, Heart Rate, Blood Pressure, SpO2, Headache, Vomiting, Seizures |
| Medication | Antiviral Given, Oxygen Therapy, ICU Admission, Medication Name, Start Date |
| Adverse Events | Event Term, Start Date, Severity, Serious, Outcome |
| Final Assessment | Study Completion Date, Study Final Status, Investigator Comments |

## CDM skills demonstrated
| Skill | How it is shown in this project |
|-------|---------------------------------|
| eCRF design | 14 forms with defined variables, field types and required fields |
| EDC database build | Visit structure, forms and fields built in Castor CDMS |
| Data entry | 10 fictional participants entered across all visits |
| Audit trail review | Reviewed who changed what and when |
| Study progress tracking | Used the dashboard to check visit completion |
| Record locking | Locked completed participant records |

## Files in this repository
- `Castor_CDMS_Mock_Study_Nipah_Virus_Infection_redacted.pdf`: 13-page walkthrough with screenshots (participants list, visit structure, form designs, data entry, audit trail, study dashboard). Personal email addresses are hidden.

## Limitations and next step
This first project focuses on study build and data capture. It does not include data validation, edit checks or query management. A second project adds these using a Type 2 Diabetes with Hypertension study.

## Tools
Castor CDMS (EDC)

## Author
Kushi | B.Pharm | Aspiring Clinical Data Associate
