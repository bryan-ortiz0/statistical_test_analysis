# Analysis of Census ACT/SAT Scores From 2017-2019 📝

Analyzing data spanning 2017 to 2019, we examine ACT participation rates, ACT composite scores, SAT participation rates, and SAT total scores, categorized by their respective census regions. The main aim is to uncover trends specific to each region and extract insights that can guide the strategic distribution of resources to areas in need.

# Data Dictionary

| Feature             | Type                        | Dataset | Description                                                                                                                                               |
| ------------------- | --------------------------- | ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| mean_of_values      | function                    | ACT/SAT | Function used to manually compute the mean                                                                                                               |
| standard_dev        | function                    | ACT/SAT | Function used to manually compute the standard deviation                                                                                                 |
| data_cleaner        | function                    | ACT/SAT | Function used to take in a string that is a number and percent symbol (%) and converts string to a float that is the decimal approximation of the percent |
| get_state_abbreviation      | function                    | ACT/SAT | Function used to change state names to their respected abbreviations                                                                                                               |
| get_census_regions      | function                    | ACT/SAT | Function used to changed abbreviated states to their respected census regions                                                                                                               |
| clean_act_2017      | function                    | ACT/SAT | Function used to clean act2017.csv                                                                                                               |
| clean_act_2018      | function                    | ACT/SAT | Function used to clean act2018.csv                                                                                                               |
| clean_act_2019      | function                    | ACT/SAT | Function used to clean act2019.csv                                                                                                                |
| clean_sat_2017      | function                    | ACT/SAT | Function used to clean sat2017.csv                                                                                                               |
| clean_sat_2018      | function                    | ACT/SAT | Function used to clean sat2018.csv                                                                                                               |
| clean_sat_2019      | function                    | ACT/SAT | Function used to clean sat2019.csv                                                                                                               |
| process_and_save_data      | function                    | ACT/SAT | Function used to merge ACT and SAT data                                                                                                               |
| act2017             | pandas.core.frame.DataFrame | ACT/SAT | ACT 2017 CSV file used to manipulate data                                                                                                                 |
| act2018             | pandas.core.frame.DataFrame | ACT/SAT | ACT 2018 CSV file used to manipulate data                                                                                                                 |
| act2019             | pandas.core.frame.DataFrame | ACT/SAT | ACT 2019 CSV file used to manipulate data                                                                                                                 |
| sat2017             | pandas.core.frame.DataFrame | ACT/SAT | SAT 2017 CSV file used to manipulate data                                                                                                                 |
| sat2018             | pandas.core.frame.DataFrame | ACT/SAT | SAT 2018 CSV file used to manipulate data                                                                                                                 |
| sat2019             | pandas.core.frame.DataFrame | ACT/SAT | SAT 2019 CSV file used to manipulate data                                                                                                                 |
| merge_2017          | pandas.core.frame.DataFrame | ACT/SAT | Merged data for act2017 and sat2017                                                                                                                       |
| merge_2018          | pandas.core.frame.DataFrame | ACT/SAT | Merged data for act2018 and sat2018                                                                                                                       |
| merge_2019          | pandas.core.frame.DataFrame | ACT/SAT | Merged data for act2019 and sat2019                                                                                                                       |

# Executive Summary

Based on the data provided and the trends observed from 2017-2019, it is clear that the region that needs the most attention is the South considerating their participation rate being the highest out of all the regions, they scored the lowest in both the ACT and SAT. The data provided by census.gov in 2020 further demonstrates the disparity of resources across all regions, especially the South.
