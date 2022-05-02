Develop paddy area map from MODIS satellite images using machine learning
==============================================================================================

--------------------

.. toctree::
   :maxdepth: 2
   :caption: In this project, I attempt to develop 2011 paddy area map of Pursat province from MODIS satellite image using Google Earth Engine, Python and unsupervised classification method in machine learning. The classification is based on the changing patterns of  Normalized Difference Vegetation Index (NDVI) time-series. These pattern of time-series data are classified into different clusters by using K-Means classifier. The processes to develop paddy area map are detailed as follows:

   paddy-area-classification/1. export-modis-images-from-gee.rst
   paddy-area-classification/2. create-mosaic.ipynb
   paddy-area-classification/3. create-timeseries.ipynb
   paddy-area-classification/4. reduce-noise.ipynb
   paddy-area-classification/5. validation-data.ipynb
   paddy-area-classification/6. kmeans-clustering.ipynb