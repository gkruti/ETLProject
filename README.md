Partners:
Louis Starr
Kruti Gandhi
ETL Final Report

Extract (E)
For our project we extracted our original data as CSV files pulled from Kaggle. The two datasets that were used are 'Medical Costs Personal Datasets' and 'Hospital Costs.’ Both datasets provide information from a different perspective, one being the insurance perspective and the other being the hospital perspective. 

Transform (T)
We cleaned the data to display the relevant columns to support our objective of variables associated with charges. The key components we focused on are 'Region', 'Gender', 'LOS (Length of stay)', 'Age', 'Level of Service.’ We joined both datasets with the age groups from birth-64. We filtered out the ages of 65 and above because that age group counts as Medicare recipients which did not represent accurate charges. 

Load (L)
	For the final database, our dataset reflected the statistical data that was relevant to both age and charges in the Insurance and Hospital categories in pgAdmin 4. We chose to show data relating to the charges because we wanted to show the difference between the perspectives of the hospital and the insurance. The type of production database that we loaded the data into was relational.  Comparatively there are many differences and influencing factors that make up the value for each age category. 

