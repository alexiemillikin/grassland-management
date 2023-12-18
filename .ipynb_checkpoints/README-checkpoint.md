# grassland-management
This repository is for the final project in EarthLabs's Earth Analytics Intro course. The project focuses on understanding and modeling how climate change will affect where grass species can live in order to best approach management and restoration projects. 

In this analysis I assess the changes in habitatbility of two different National Grasslands for Sorghastrum nutans (L.) Nash, a common native grass throughout North America. Using soil pH, elevation, and slope aspect as constants, and varying precipitation, I model the habitability of Pawnee and Cimarron National Grasslands for the years 2050 and 2099 under two different emissions scenarios, scenario 4.5 and 8.5, and compare these to historical habitability in the year 1980.

This project can be viewed on the web using this [link](https://alexiemillikin.github.io/grassland-management/).

## Repository Structure
All code for this project can be found in the Grasslands.ipynb file.

## Instructions for running code
The Grasslands.ipynb file runs using the [earth-analytics-python-env](https://github.com/earthlab/earth-analytics-python-env/blob/main/environment.yml). Two additional packages need to be downloaded, scikit-fuzzy and rasterio, using the following code:
conda install -c conda-forge scikit-fuzzy
conda install -c conda-forge install rasterio