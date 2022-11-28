[![License](https://img.shields.io/badge/License-GPL%203.0-green)](https://opensource.org/licenses/GPL-3.0)

# Clinical dashboard  
  
 A lightweight R Shiny app designed for exploration of clinical data.  
   
 3 files are required:  
 1. Demographics table, tall format, with headers: SUBJECT_ID, VARIABLE_NAME, VARIABLE_VALUE  
 2. Events table, tall format, with headers: SUBJECT_ID, EVENT_NAME, EVENT_DATETIME   
 3. Measurements table, tall format, with headers: SUBJECT_ID, MEASUREMENT_NAME, MEASUREMENT_DATETIME, MEASUREMENT_VALUE, UNIT  

Datetime values must have the format: YYYY-MM-DD HH:MM:SS
