# metaculus-rpdm-data
Data associated with the manuscript titled "Utility of human judgment ensembles during times of pandemic uncertainty: A case study during the COVID-19 Omicron BA.1 wave in the United States". 
These were collected as part of the Real-Time Pandemic Decision Making Exercise conducted by the University of Virginia Biocomplexity Institute on the Metaculus platform in collaboration with Virginia Department of Health. For more details, see [here](https://www.metaculus.com/tournament/realtimepandemic/)


### question_lookup.csv

Contains metadata for the questions (identified by round id and question id) including publishing date, closing date, and if it was a numeric/date forecast along with the forecast range.

### user_pred.csv

Contains number of unique users and predictions per question (identified by round id and question id).

### misc/va_federal_doses.csv

Contains daily timeseries of first and second doses federal doses administered in Virginia. This is provided separately since the public data source only contains the cumulative [count](https://data.virginia.gov/Government/VDH-COVID-19-PublicUseDataset-Vaccines-DosesAdmini/28k2-x2rj).

### public/

This folder contains the time series of Metaculus prediction for each question (file naming convention: [round id]_[question id].csv). Each file contains the timestamp of update along with the 25th, 50th, and 75th percentiles of the prediction. 
