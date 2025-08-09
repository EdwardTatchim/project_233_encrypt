# 233_Encrypt 
# Privacy Protections in Anonymized Medical Records: 
# A Comprehensive Study of Sensitive Diagnostic Attributes in MIMIC-IV

## Edward Tatchim, Sanjiv M. Narayan, Rohan Krishnamurty
## Datasci 233, Fall 2024, Session 1; v0.2, 11/24/2024

### Project Goals
To study privacy guarantees of patients in MIMIC-IV, who presented to the Emergency room of Harvard Teaching Hospitals from 2008 to 2019. While this data is rigorously de-identified it includes ICD10 diagnostic codes, which may be considered sensitive attributes. The goal of this project is to quantify the risk of attribute or membership disclosure for various selected ICD10 codes using k-anonymity, L-diversity and t-closeness at baseline. We then intend to study how well the risk of disclosure and information gain could be mitigated by a series of generalization and data suppression techniques. We use rigorously de-identified real-world medical data in the form of MIMIC-IV released through MIT and Beth Israel Hospital, and will study ICD10 codes including but not limited to alcohol and substance abuse, in parallel with the DATASCI 233 coursework. This work is in preparation for submission to the Scientific sessions of the Heart Rhythm Society 2025.

### Data Use Permissions
To access data for our project, we turned to the Physionet resource (https://mimic.mit.edu/). All team members proceeded to complete specific training in human data handling, HIPAA and confidentiality. Each team member obtained a CITI certification to work on human data, which was submitted and formally approved by the Physionet organization (Harvard/Beth Israel Hospital; Massachussetts Institute of Technology) **prior to starting this project.** Certifications and approvals for each team member are available upon request. Only de-identified data will be shown during presentations and publications.

### Data Resource
MIMIC-IV is a publicly available de-identified database sourced from the electronic health records of the Harvard University/Beth Israel Deaconess Medical Center. For this study, we used a subset which contains ICD10 codes and subject demographics. 
https://physionet.org/content/mimic-iv-ecg-ext-icd-labels/1.0.1/ Data available includes patient measurements, orders, diagnoses, procedures, treatments, and deidentified free-text clinical notes.  We use the core table that allows retrieval of different kinds of discharge diagnoses (as ICD-10-CM codes) for a given sample in MIMIV-IV-ECG. The initial scope of this project does not include processing of detailed clinical data (https://physionet.org/content/mimiciv/2.2/) or ECG waveforms (https://physionet.org/content/mimic-iv-ecg/1.0/), which would require more time than available for this project. 
