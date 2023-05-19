# Project_1_Covid_Data
Group 7. Data Analytics Project 1


### Data Sources:
	Data was sourced from EARN/EPI - "EARN SLFRF Workbook for Q4 2022"  and
	CDC - "COVID-19 Vaccinations in the United States, Jurisdiction":
	https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc

	###Timeframe: 
		post March 11, 2021 – end of 2022


## Project Summary
- All US states were reviewed for federal grant spending.
- Differing grant qualification criteria per state was not considered.



## Major Findings Summary:
	There is not a strong correlation between state or local government use of SLFRF money for vaccination projects and 	vaccination rates in those states, at least on the variables that were measured in this project.


### Methods used for Analysis:
- Import raw data as csv
- Drop rows with NA values  
- Clean column values with string replace functions
- Cast strings as numeric where needed
- Pandas groupby to sum or count values
- Created reduced DFs for specific visuals
- Created calculated percentage columns within relevant DataFrames
- Defined functions for efficient code