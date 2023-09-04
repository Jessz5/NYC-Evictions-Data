# NYC Evictions Data Cleaning

This repository contains cleaned eviction data for New York City from 2017 to early 2022. The dataset is cleaned in two different versions:

- **NYC_Evictions_Dataset_2017_to_2022:** In this version, all entries with null values in any column were removed, resulting in a cleaned dataset with no missing values.

- **NYC_Evictions_Dataset_2017_to_2022_GeoPy:** In this version, an attempt was made to fill in the missing latitude and longitude values using the Geopy library and the Notimantim geocoding service.

## Data Source

The raw eviction data used in this cleaning process was obtained from NYC OpenData provided by the Department of Investigation (DOI). This dataset covers eviction records in New York City from 2017 to early 2022.

The purpose of this repository is to provide a clean dataset for further analysis, which has been performed using Tableau or other data analysis tools.
