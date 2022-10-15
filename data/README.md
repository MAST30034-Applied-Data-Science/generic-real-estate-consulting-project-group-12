### Data 
Dataset uploaded are: 
#### 1. Population data 
Population data are the annual census data from 2001 to 2021 sourced from ABS, where population are counted by region, uploaded data file in excel workbook format with 2022 population forecast based on average of past 5 years data (i.e., 2016 to 2021).
#### 2. Criminal_incidents.xlsx
The criminal incidents dataset contains number of incidents recorded from 2013 to 2022
#### 3. Income.xlsx
The income dataset contains number of earners, median age of earners, sum/median/mean income for all postcodes from 2019 to 2022
#### 4. POSTCODE_POLYGON.shp/SA2 ERP GeoPackage 2021 (ASGS2021).gpkg
Shape file used to draw graph
#### 5. Recorded_Offences.xlsx/recorded offences.csv/recorded offences.xlsx
The recorded offence dataset contains number of  recorded offence count from 2013 to 2022
#### 6. Sex & Age by Year
Sex and age by year dataset are regional, sourced from ABS starting from 2001 to 2021. It contains yearly male and female count by age group. Sex ratio for 2022 has been forecasted by averaging change from 2016 to 2021. Age groups are separated into 18 buckets with 5-year gap (from 0 – 85+) each (note: this might need to be aggregate at some point with further group discussion). 
#### 7. attribute_conbined.csv
This dataset contains all the externel attributes downloaded through OpenStreetMap 
#### 8. cleaned_complete.csv/cleaned_data.csv/cleaned_data_groupby.csv/cleaned_data_groupby_predict.csv/finalized.csv/house_combined.csv/merge_data_v2.csv
The datasets that before and after cleaning which will be used to modelling and prediction
#### 9. cpi.csv
The cpi value from 2019 to 2025
#### 10. criminal incidents2022-2013.xlsx
The criminal incidents from 2013 to 2022
#### 11. distance_to_melbourne_central
The distance to melbourne center via routes obtained by Open Route Service
#### 12. gdp.xlsx
The gdp value from 2019 to 2025
#### 13.Hospital data (hospital_csv)
All the hospital data scraping from https://vahi.vic.gov.au/hospital-and-health-services
#### 14.population_forcasting.csv
population forcasting for future five years of each suburb
#### 15. postcode_in_VIC.csv
Contains all the information about suburbs with postcode
#### 16. school.csv
ALl the primary and secondary schools in VIC
#### 17. shopping center.csv/shopping_with_postcode.csv
All the shopping center in VIC
#### 18.suburb.xltx
suburb file contains all the main suburbs in VIC, which will be used to extract suburb id
#### 19.suburb_id.csv
This file contains suburb id which obtains using api by v1/addressLocators 
#### 20.shopping center.csv
The name and suburb of the shopping center in Victoria.
#### 21.agent_list.csv and agent_list2.csv
The agent list file contains all the agent that sells/rents properties in Victoria, which obtained through https://developer.domain.com.au/docs/latest/apis/pkg_agents_listings/references/agencies_search using api
#### 22.agent_info_id.csv
This file contains all the agent id that sells/rent houses in Victoria
#### 23.house_combined.csv
This file contains all the properties in VIC through https://developer.domain.com.au/docs/latest/apis/pkg_agents_listings/references/agencies_getlistings using api
#### 24.routes.json
This file is used to extract route id and route type that will be used to extract stops of different transportation
#### 25.stops_file_0.json/stops_file_1.json/stops_file_2.json/stops_file_3.json/stops_file_4.json
The stops file contains all the stops in VIC, where stops_file_0.json contains train stops, stops_file_1.json contains Tram stops, stops_file_2.json contains bus stops, stops_file_3.json contains Vline stops, stops_file_4.json contains Night Bus stops
#### 26.train_stops_file.csv/tram_stops_file.csv/bus_stops_file.csv/vline_stops_file.csv
These csv files contains all the stops information with suburb name and postcode
#### 26. year_school_address.txt
The future built school in VIC for the next two years

