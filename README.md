# defend-prognosis

Generate machine learning models to predict severity in COVID-19 and check models between hospitals. This repository contains two .csv files and five notebooks:

##notebooks

### bp_integration and hsl_integration

Contains all codes used to integrate the raw data.

In the original file tests, there are some cases when the same test have similar but divergent label. This cases were resolved with the help of an expert. The file 'HSL_Exames_4_labels.csv' have this issues corrected. 
The corrected file and the correspondent codes could be found at github.com/gabivaleriano/defend-prognosis.

### preprocessing_bp_severity_hospitalized and preprocessing_hsl_severity_hospitalized.ipynb

Contains all codes used do preprocessing data from Hospitals Beneficência Portuguesa and Sírio Líbanes. Data available at https://repositoriodatasharingfapesp.uspdigital.usp.br/

### models_training

Contains all codes used to generate machine learning predictive results for five hospitals. Data used contain routine attendance parameters collected up to four days after initial attendance.

## .csv files

###hosp1 and hosp2

Contains the data resulted from preprocessing described in the notebooks, hosp1 refers to the Hospital Sirio Libanês data and hosp2 refers to the Hospital Beneficência Portuguesa data.
