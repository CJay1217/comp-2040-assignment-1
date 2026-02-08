# U.S. cereal rye winter cover crop growth database

We compiled data on cereal rye winter cover crop performance metrics, agronomic practices, and soil properties across the eastern half of the United States. The dataset includes a total of 5,695 cereal rye biomass observations across 208 site years between 2001-2022 and encompasses a wide range of agronomic, soil, and climate conditions.

## Description of the data and file structure

Data files are numbered and described in the 1_data_dictionary.csv file, and an R script to reproduce the figures is provided. 1_data_dictionary.csv	provides a definition of variables for the following files. 2_study_metadata.csv provides detailed site location, study design information, the DOI for any published data, and methods information for any unpublished data. 3_rye_data.csv provides cereal rye-related data associated with biomass observations. 4_agronomic_data.csv provides agronomic management data general to each study. 5_soil_data.csv provides oil sample data and/or general site soil data. Empty cells or cells containing NA indicate that no data were available. 

## Code/Software

The R script provided was run using the "here" package v1.0.1, the "tidyverse" package v1.3.2, and the "lubridate" package v1.8.0. The figures were producing using R v4.1.3.

\#Disclaimer
This code is provided on an "as is" basis and the user assumes responsibility for its use. The authors have relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information.
