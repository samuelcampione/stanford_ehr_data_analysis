# EHR Data Analysis

Vast amounts of clinical data stored is stored in silos around the world. I will demonstrate some of the possible analyses using a dataset I recieved from Stanford HealthCare recently. 

This dataset contains 1000 patients and was used for machine learning. The data is stored in a standardized Common Data Model (CDM) structure in which tables are designed to be linked through standardized methods. The tables include person, death, location, condition_occurence, drug_exposure, and concept (a vocabulary table linking ID's to names).

In this repository:
- The [python notebook]() used to generate visualizations 
- The [final report]() in presentation form

# Key Visualizations

## Distribution of patients in different states

<img src="https://github.com/samuelcampione/stanford_ehr_data_analysis/blob/main/visualizations/geographic_distribution_of_patients.png" width="700"/>


## Condition prevalence in 2010
<img src="https://github.com/samuelcampione/stanford_ehr_data_analysis/blob/main/visualizations/most_prevalent_conditions_2010.png" width="600"/>

## Average number of drugs per person
<img src="https://github.com/samuelcampione/stanford_ehr_data_analysis/blob/main/visualizations/duration_of_simvastatin_violinplot.png" width="300"/>

## Average duration that the Simvastatin 40 mg
<img src="https://github.com/samuelcampione/stanford_ehr_data_analysis/blob/main/visualizations/duration_of_simvastatin_violinplot.png" width="300"/>
