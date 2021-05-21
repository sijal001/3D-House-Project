<h1 align="center"> <strong>3D House Project</strong> </h1>
 
 
<img src="https://images.pexels.com/photos/3879060/pexels-photo-3879060.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="Italian Trulli" width="1000" height="550" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;">
 
> <p> <strong> Build a data to model a house in 3D with only a home address. </strong> </p>
 
---
 
## **Table of Contents**
Your sections headers will be used to reference the location of destination.
 
- [Description](#description)
- [How To Use](#how-to-use)
- [Repo Artitecture](#repo-artitecture)
- [Next Step](#next-step)
- [License](#license)
- [Author Info](#author-info)
 
---
 
## **Description**
 
<p align="justify">
LIDAR PLANES are active in the Geospatial industry. They would like to use their data to launch a new branch in the insurance business. So, they need to build a solution with their data to model a house in 3D with only a home address.
</p>
<p align="justify">
<b>Learning Objectives</b>:
 
* To be able to search and implement new librairies
* To be able to read and use shapefiles
* To be able to read and use geoTIFFs
* To be able to render a 3D plot
* To be able to present a final product
</p>
<br/>
 
## **Technologies**
<br/>
 
| Library       | Used to                                        |
| ------------- | :----------------------------------------------|
| folium        |to manipulate data then visualize it in a map   |
| geopy         |to get the longitude and latitude of a address  |
| glob          |to get all the file with given extension        |
| natsort       |to sort files with number in the file           |
| numpy         |to work around multi-dimensional of generic data|
| os            |to work around the system path.                 |
| osgeo         |to work raster file as a GDALDataset            |
| plotly        |to generate interactive 3d plotting             |
| pyproj        |transform 'EPSG:4326' to 'EPSG:31370' coordinate|
| rasterio      |to open '.tif' file to calculate canopy height  |
| rioxarray     |load raster metadata support masking and scaling|
| shutil        |to remove, move, copy files.                    |
| webbrowser    |to open browser, google map for verification    |
 
 
[**↥ Back To The Top**](#table-of-contents)
 
---
 
## **How To Use**
 
### **Installation** 
 
`Python Ver. '3.8.0'`
 
**Note:** Just use the command below to install the required library with the correct version to run the program smoothly.
 
`pip install -r requiement.txt`
 
<br/>
 
**DSM and DTM data**
<br/>
**Storage Requirement:** 80 GB 
<br/>
* ***Method 1:*** Manually Download all the files from link save to the respective folder. Unzip all the folders and delete the zip folders.
    * [DSM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m)
    * [DTM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m)
 
* ***Method 2:*** Run "Download DSM_DTM.ipynb" to do the process automatically.
 
 
1. Setup python environment  `3.8.0`.
2. Install all libraries `pip install -r requirements.txt`.
3. Download important ".tif" files `Download DSM_DTM.ipynb`.
4. Run the `3d_house.ipynb` in jupyter notebook.
5. Enter the address in the given format.
6. Run all code.
7. Receive interactive 3D diagram and '.png' format image of the location.
 
[**↥ Back To The Top**](#table-of-contents)
 
---
 
## **Repo Artitecture**
```
3D-House-Project
│   README.md               :explains the project
│   requirements.txt        :packages to install to run the program
│   .gitignore              :specifies which files to ignore when pushing to the repository
│
│   Download DSM_DTM.ipynb  :script to download all DSM and DTM files, unzip it and delete zip files.
│   3d_House.ipynb          :script to run in order to start the program
│   
│   3D Image                :directory contains all 3d image of the location that ever searched.
│   search address data     :directory contains the '.tif' files of dsm, dtm and canopy height model of all search addresses.
│   DTM             :directory contains all the DTM '.tif' files.
│   DSM             :directory contains all the DSM '.tif' files.
```
 
[**↥ Back To The Top**](#table-of-contents)

---
 
## **Result Preview**
 <img src="./3D Image/Koningin Astridplein 27 2018 Antwerpen.png" alt="Italian Trulli" width="350" height="300" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img src="./3D Image/Bolivarplaats 20, 2000 Antwerpen.png" alt="Italian Trulli" width="350" height="300" >
<br/>

[**↥ Back To The Top**](#table-of-contents)

---
 
## **Next Step**
 
* Optimize code to have the result as fast as possible.
* Adding features like 
  * The living area of the house in m²
  * How many floors
  * If there is a pool
  * The vegetation in the neighborhood, etc...
* Better visualization.
 
[**↥ Back To The Top**](#table-of-contents)
 
---
## **License**
 
Copyright (c) [2021] [Sijal Kumar Joshi, Simon Snyders, Vincent Rolin]
 
<p align="justify">
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
</p>
<p align="justify">
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
</p>
<p align="justify">
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
</p>
 
[**↥ Back To The Top**](#table-of-contents)
 
---
 
## **Authors Info**
 
- Linkedin - [Sijal Kumar Joshi](https://www.linkedin.com/in/sijal-kumar-joshi-b1545584/)
- Github   - [Sijal Kumar Joshi](https://github.com/sijal001)
 
[**↥ Back To The Top**](#table-of-contents)