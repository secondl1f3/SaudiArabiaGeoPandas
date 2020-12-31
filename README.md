# Saudi Arabia Maps Using GeoPandas

### Requirements:

* Python >= 3.5
* Pandas: open source data analysis and manipulation tool, built on top of the Python programming language.
* geopandas >= 0.5.0: an open-source package that helps users work with geospatial data. 
* Matplotlib: a comprehensive library for creating static, animated, and interactive visualizations in Python.
* Contextily: a package to retrieve tile maps from the internet.
* Cartopy: is a Python package designed for geospatial data processing in order to produce maps and other geospatial data analyses.
* Jupyter Notebook: an open source web application that you can use to create and share documents that contain live code, equations, visualizations, and text. 
* Conda: an open source package management system and environment management system that runs on Windows, macOS and Linux. 

### Set the environment
```sh
# ensure you have at least conda >=4.6 
conda update conda 
# setting the configuation so all packages come from the conda-forge channel 
conda config --add channels 
conda-forge conda config --set channel_priority strict 
# navigate to the folder material 
cd .../geopandas-tutorial/ 
# creating the environment 
conda env create --name geopandas-tutorial --file environment.yml 
# activating the environment 
conda activate geopandas-tutorial
```

### Download all the shapefile that use in this project:
[Google Drive]

View the run application here:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/secondl1f3/SaudiArabiaGeoPandas/HEAD?filepath=%2Fblob%2Fmain%2Fsaudi%2520geopandas.ipynb)


[Google Drive]: <https://drive.google.com/drive/folders/1_Y6rveEyZd_KkKiHebEQJjuIAHdMdLwg?usp=sharing>
