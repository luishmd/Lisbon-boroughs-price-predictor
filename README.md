# Background
Final report of the IBM Data Science Professional Certificate


# Description
The goal is to be able to predict property prices of Lisbon's boroughs from data on population size, area, and number of venues types, e.g. number of restaurants, gyms, bars.


## Output
Multiple linear correlation between borough's property prices and a set of features. The set of features to use corresponds to the features which maximize R**2

## Input data
1. Lisbon borough's info
	- Names
	- Location (lat., long.)
	- Property prices
	- Population
	- Area

2. Lisbon venue's info
	- Name
	- Location
	- Category:
		* Arts, entertainment and nightlife
		* Food and drink
		* Supermarkets and groceries
		* Shopping
		* Historic sites and museums
		* Hotels and accomodation
		* Athletics and sports
		* Transport
		* Public buildings
		* Health and education buildings
		* Outdoors


# Technologies used
The script is implemented in jupyter notebook (Lisbon boroughs price predictor - Notebook.ipynb).
For further info on the libraries used, please see section *How to use it*


# Status
This work is complete.


# Identified bugs
None.


# How to use it
1. Make sure you have the following libraries installed in a python 3.x environment
	- os
	- pandas
	- requests
	- bs4
	- numpy
	- seaborn
	- matplotlib
	- geopy
	- scikit-learn
	- folium

2. Run the jupyter notebook *Lisbon boroughs price predictor - Notebook.ipynb*
