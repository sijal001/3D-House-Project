# 3D-House-Project

- Repository: `3D_houses`
- Duration: `2 weeks`
- Deadline: `25/02/21 5:00 PM`


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

* **Python version:** `3.8.0`

**Imporant Libaries:**

| Library       | Used to                                        |
| ------------- | :----------------------------------------------|
| folium	|to manipulate data then visualize it in a map   |
| geopy		|to get the longitude and latitude of a address |
| glob		|to get all the file with given extension        |
| natsort	|to sort files with number in the file		 |
| numpy		|to work around multi-dimensional of generic data|
| os		|to work around system path.			 |
| osgeo		|to work raster file as a GDALDataset  		 |
| plotly	|to genereate interactive 3d plotting             |
| pyproj	|transform 'EPSG:4326' to 'EPSG:31370' coordinate|
| rasterio	|to open '.tif' file to calculate canopy height  |
| rioxarray	|load raster metadata support masking and scaling|
| shutil	|to remove, move, copy files.			 |
| webbrowser	|to open browers, open google map for verfication|

**Note:** Just use command below to install the required libary with correct version to run the program smoothly.

"pip install -r requiement.txt"


# **DSM and DTM data**

* **Storage Requirement:** 80 GB 

* ***Method 1:*** Manually Download all the file from link save to the respective folder. Unzip all the folder and delete the zip folders.
    * [DSM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m)
    * [DTM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m)

* ***Method 2:*** Run "Download DSM_DTM.ipynb" to do process automatically.


# Architecture

```
3D-House-Project
│   README.md               :explains the project
│   requirements.txt        :packages to install to run the program
│   .gitignore              :specifies which files to ignore when pushing to the repository
│
│   Download DSM_DTM.ipynb  :script to download all DSM and DTM files, unzip it and delete zip files.
│   3d_House.ipynb          :script to run in order to start the program
│   
│   3D Image          	    :directory contains all 3d image of the location that ever searched.
│   search address data	    :directory contains the '.tif' files of dsm, dtm and canopy height model of all search addresses.
│   DTM		    	    :directory contains all the DTM '.tif' files.
│   DSM		    	    :directory contains all the DSM '.tif' files.
```

---

# Instruction
#### How to get 3d_location plotting

1. Setup python environment  `3.8.0`.
2. Install all libaries `pip install -r requirements.txt`.
3. Download important ".tif" files `Download DSM_DTM.ipynb`.
4. Run the `3d_house.ipynb` in jupyter notebook.
5. Enter the address in the given format.
6. Run all code.
7. Recieve interactive 3D diagram and '.png' format image of the location.

---
# Next Step

* Optimize code to have the result as fast as possible.
* Addding features like 
	* The living area of the house in m²
	* How many floors
	* If there is a pool
	* The vegetation in the neighborhood, etc...
* Better visualization.