[![License](https://img.shields.io/badge/License-GPL%203.0-green)](https://opensource.org/licenses/GPL-3.0)

# Clinical dashboard  
  
 A lightweight R Shiny app designed for exploration of clinical data.  
   
 3 files are required:  
 1. Demographics table named DEMOGRAPHICS.csv, tall format, with headers: SUBJECT_ID, VARIABLE_NAME, VARIABLE_VALUE  
 2. Events table named EVENTS.csv, tall format, with headers: SUBJECT_ID, EVENT_NAME, EVENT_DATETIME   
 3. Measurements table named MEASUREMENTS.csv, tall format, with headers: SUBJECT_ID, MEASUREMENT_NAME, MEASUREMENT_DATETIME, MEASUREMENT_VALUE, UNIT  

Datetime values must have the format: YYYY-MM-DD HH:MM:SS (24h format)

Synthetic data for 100 patients, plus the script used to generate the synthetic data, are included.  
