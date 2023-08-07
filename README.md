# Analysis of Census ACT/SAT Scores From 2017-2019 📝

Analyzing data spanning 2017 to 2019, we examine ACT participation rates, ACT composite scores, SAT participation rates, and SAT total scores, categorized by their respective census regions. The main aim is to uncover trends specific to each region and extract insights that can guide the strategic distribution of resources to areas in need.

# Data Dictionary

| Feature             | Type                        | Dataset | Description                                                                                                                                               |
| ------------------- | --------------------------- | ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| mean_of_values      | function                    | ACT/SAT | Function used to manually compute the mean                                                                                                               |
| standard_dev        | function                    | ACT/SAT | Function used to manually compute the standard deviation                                                                                                 |
| data_cleaner        | function                    | ACT/SAT | Function used to take in a string that is a number and percent symbol (%) and converts string to a float that is the decimal approximation of the percent |
| state_abbreviations | dict                        | ACT/SAT | Dictionary used to change state names from their full name to their abbreviated letters                                                                  |
| census_regions_dict | dict                        | ACT/SAT | Dictionary used to categorize abbreviations with their respected census regions                                                                           |
| act2017             | pandas.core.frame.DataFrame | ACT/SAT | ACT 2017 CSV file used to manipulate data                                                                                                                 |
| new_act2017_dict    | dict                        | ACT/SAT | Dictionary used to rename column names as lower case                                                                                                      |
| act2018             | pandas.core.frame.DataFrame | ACT/SAT | ACT 2018 CSV file used to manipulate data                                                                                                                 |
| new_act2018_dict    | dict                        | ACT/SAT | Dictionary used to rename column names as lower case                                                                                                      |
| act2019             | pandas.core.frame.DataFrame | ACT/SAT | ACT 2019 CSV file used to manipulate data                                                                                                                 |
| new_act2019_dict    | dict                        | ACT/SAT | Dictionary used to rename column names as lower case                                                                                                      |
| sat2017             | pandas.core.frame.DataFrame | ACT/SAT | SAT 2017 CSV file used to manipulate data                                                                                                                 |
| new_sat2017_dict    | dict                        | ACT/SAT | Dictionary used to rename column names as lower case                                                                                                      |
| sat2018             | pandas.core.frame.DataFrame | ACT/SAT | SAT 2018 CSV file used to manipulate data                                                                                                                 |
| new_sat2018_dict    | dict                        | ACT/SAT | Dictionary used to rename column names as lower case                                                                                                      |
| sat2019             | pandas.core.frame.DataFrame | ACT/SAT | SAT 2019 CSV file used to manipulate data                                                                                                                 |
| new_sat2019_dict    | dict                        | ACT/SAT | Dictionary used to rename column names as lower case                                                                                                      |
| merge_2017          | pandas.core.frame.DataFrame | ACT/SAT | Merged data for act2017 and sat2017                                                                                                                       |
| new_merge2017_dict  | dict                        | ACT/SAT | Dictionary used to rename column names as lower case and underscores                                                                                      |
| merge_2018          | pandas.core.frame.DataFrame | ACT/SAT | Merged data for act2018 and sat2018                                                                                                                       |
| new_merge2018_dict  | dict                        | ACT/SAT | Dictionary used to rename column names as lower case and underscores                                                                                      |
| merge_2019          | pandas.core.frame.DataFrame | ACT/SAT | Merged data for act2019 and sat2019                                                                                                                       |
| new_merge2019_dict  | dict                        | ACT/SAT | Dictionary used to rename column names as lower case and underscores                                                                       

# Executive Summary

Based on the data provided and the trends observed from 2017-2019, it is clear that the region that needs the most attention is the South considerating their participation rate being the highest out of all the regions, they scored the lowest in both the ACT and SAT. The data provided by census.gov in 2020 further demonstrates the disparity of resources across all regions, especially the South.
