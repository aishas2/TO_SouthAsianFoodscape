# South Asian Immigrants and Foodscapes in Scarborough and Markham, Ontario
Code from my MA Thesis, Immigrant Impact: Deconstructing the Production of the South Asian Immigrant Food Environment. This thesis was written at the University of Toronto in 2024 under the supervision of Dr. Michael Widener and Dr. Lindsey Smith.

## Abstract
In Scarborough and Markham in the Greater Toronto Area, immigrant-run ethnic businesses can provide healthy, affordable, and culturally appropriate foods to newcomer communities. They may also provide economic opportunities for immigrants that are not otherwise available. Therefore, this thesis investigates the distinct impacts of different South Asian national groups on the food retail environment in the adjacent regions of Scarborough and Markham from 1996 to 2016. To do this, emerging hot spot analysis and spatial lag panel models with time fixed effects were employed. Contextualizing quantitative results with historical newspaper articles viewed through a two-way integration process framework, this study found that different South Asian immigrant groups and retailers emerge in distinct spatio-temporal patterns and have varying influences on the built food retail environment. Overall, this study emphasizes the cultural differences between South Asian immigrant national groups that manifest in the built environment and deconstructs the South Asian monolith.

*This repository includes data used for this project. Analysis code provided in R code in a quarto document.*

## Retailer Data
Retailer data was obtained from the Yellow Pages Grocery and Restaurant Sections for Scarborough and Markham for the years 1996, 2001, 2006, and 2016. These retailer names and addresses were manually inputted into and classified into retailer categories in an excel sheet. The process used to clean and geocode this data was completed in Python in a Jupyter Notebook and may be found in the "YP_Cleaning" folder. The final data and accompanying metadata used in the analysis may be found in the [data](data) folder under spation_YP.geojson.

## Census tract apportionment
The process and crosswalk tables used to apportion census data were obtained from [Jeff Allen's CLTD repository](https://github.com/jamaps/CLTD/tree/master).
