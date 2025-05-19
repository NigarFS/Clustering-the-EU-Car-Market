# Clustering-the-EU-Car-Market
This project's goal is to set the stage for future research on the EU auto industry by offering preliminary examinations of market segmentation and its variations among EU member states for the years 2010–2022.

This directory contains all relevant files that serve as supplemental material to the project.

All files found in the "Code_and_Supplemental_Material"-section have been run as is without issues:
	
	- The file ending in "_ac_ay.R" includes everything related to the hierarchical clustering procedure
	- In order to work with the Irish subsets this file has been altered in an additional run 
	  (setting country to just include Ireland in relevant periods)	
	- The file ending in "_K_Means.R" includes everything related to the K-Means clustering
	- The associated cluster counts can be found in the .csv-file which is also used in the code itself
	- The file ending in "-Cleaning_finalized.R" shows the procedure used to do almost all cleaning
	- We only had to the splitting into the year/country-subsets outside of our file.
	  Since the cloud-server we were using early on was limited in memory as well, we abandonded that approach.
	  The splitting was then done with the help of Dr. Dannemann.
	  Other than this step everything has been done without external help.

The cleaned data can be found in the "Data"-section.

All results can be found in the "Results"-Section:
	
	- Each country has a dedicated subdirectory
	- Dendrograms and Scree Plots are presented for every country-year-combination
	- The results of the K-means clustering can be found in the .xlsx-file in each country's subdirectory

The countries are named abbreviated the following:

AT Austria
BE Belgium
BG Bulgaria
CY Cyprus
CZ Czechia
DE Germany
DK Denmark
EE Estonia
ES Spain
FI Finland
FR France
GR Greece
HU Hungary
IE Ireland
IT Italy
LT Lithuania
LU Luxembourg
LV Latvia
MT Malta
NL Netherlands
PL Poland
PT Portugal
RO Romania
SE Sweden
SI Slovenia
SK Slovakia
