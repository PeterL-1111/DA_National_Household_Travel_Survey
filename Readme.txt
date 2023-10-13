Introduction

This repository contains the Python code and methodologies used for various transportation analyses in the Richmond Metropolitan Planning Organization (MPO) area in Virginia. The studies incorporate various factors such as household size, number of vehicles, trip purposes, and trip lengths to generate insightful metrics. Matrix multiply and aggregation were used for trip table calculation. Weighting factors are applied to ensure the representativeness of the data.

The major analyses done include National Household Travel Survey trip rates calculation, trip distribution calibration, average trip time validation.

Key Highlights
Data Cleaning and Filtering: Multiple Jupyter notebooks are responsible for cleaning and filtering the data. They remove duplicates, keep only the necessary columns, and ensure data integrity.

Spatial Relevance: Notebooks use GeoPandas to verify if household locations and trip origins are within the area of interest (defined by a shapefile). This ensures that the analysis is spatially relevant.

Trip Categorization: Trips are categorized into different types like Home-Based Work (HBW), Home-Based Other (HBO), and Non-Home-Based (NHB) using Python functions.

Trip Rates Calculation: Core notebooks calculate trip rates based on various criteria such as household size (HHSIZE) and number of vehicles (HHVEHCNT). The code is optimized for performance and readability.

Peak Hour Analysis: A new notebook focuses on analyzing peak hour traffic, incorporating factors like trip purpose and trip length. It uses data from both CSV and DBF files and merges them for comprehensive analysis.

Extendable for Visualizations: Although not explicitly shown in the code, you can easily extend it to include various visualizations such as trip rate distributions among different segments.

Disclaimer - Data Security and Sources
Data Sources
The data used in these analyses has been obtained from the Virginia Department of Transportation (VDOT) and the National Household Travel Survey (NHTS). The data is further refined for these specific studies.

Data Access
Due to data integrity and privacy concerns, the raw data is not provided in this repository. You may request access to the data from the Travel Demand Modeling Group at the Virginia Department of Transportation.
