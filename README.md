# 3D-House-Project

* Repository: 3D_houses
* Type of Challenge: Learning & Consolidation
* Duration: 2 weeks
* Deadline: 25/02/21 5:00 PM
* Deployment strategy : Github page | Powerpoint | Jupyter Notebook | Webpage | App
* Team challenge : solo

# Mission objectives

Consolidate the knowledge in Python, specifically in :

* NumPy
* Pandas
* Matplotlib


# Learning Objectives

* To be able to search and implement new librairies
* To be able to read and use shapefiles
* To be able to read and use geoTIFFs
* To be able to render a 3D plot
* To be able to present a final product


# The Mission

We are LIDAR PLANES , active in the Geospatial industy. We would like to use our data to launch a new branch in the insurrance business. So, we need you to build a solution with our data to model a house in 3D with only a home address.

---

# About Running the Program

* **Python version:** 3.8.0
* **Storage Requirement:** 80 GB 

**Imporant Libaries:**

* os
* shutil
* folium
* rioxarray
* numpy
* plotly
* glob
* osgeo
* pyproj
* natsort
* geopy
* rasterio

**Note:** Just use command below to install the required libary with correct version to run the program smoothly.

"pip install -r requiement.txt"


**Important link**
* ***Method 1:*** Manually download throught the link
* ***Method 2:*** Download automatically using "Download DSM_DTM.ipynb" 


Download all the file from link save to the respective folder.
Unzip all the folder and delete the zip folders.

* [DSM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m)
* [DTM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m)



# Directory

* ***3D Image***
This directory contains all 3d image of the location that ever searched.

* ***DTM***
This directory should contains all the '.tif' files downloaded from [DTM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m)

* ***DSM***
This directory should contains all the '.tif' files downloaded from [DSM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m)

* ***search address data***
This directory contains the '.tif' files of dsm, dtm and canopy height model of all search location.

---


# How to get 3d_location ploting

* After setting up the enviroment and downloading all requrired files.
* Run the "3d_house.ipynb" in jupyter notebook
* Enter the address in the given format.
* Run all code
* recieve the 3D_proting of the location.
