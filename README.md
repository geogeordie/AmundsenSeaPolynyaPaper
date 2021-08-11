# AmundsenSeaPolynyaPaper

Find here the scripts for processing data and making figures in the paper:

Macdonald GJ, Ackley SF, Mestas-Nuñez AM (submitted) Evolution of the Amundsen Sea Polynya, Antarctica. The Cryosphere.

Many of the scripts could be made more efficient, and they may include redundant lines that have not been deleted after testing various things.
Get in touch with grant.macdonald@utsa.edu if you have any questions.

All processing was done with free software. All processing scripts for Python, except where indicated. The exceptions are one step of data processing was done
with GDAL directly in the Terminal on a Mac and Video S1 was created in Google Earth Engine. Other processing was done manually in QGIS, as indicated.

BedMachine Antarctica V2 was downloaded from: https://nsidc.org/data/nsidc-0756. 
Sea ice concentration data was downloaded from: https://seaice.uni-bremen.de. 
ERA5 climate data was downloaded from: https://cds.climate.copernicus.eu. 
Sentinel-1 images were processed in Google Earth Engine or downloaded from: https://asf.alaska.edu
The MODIS image used for Fig. 1b was downloaded from: https://worldview.earthdata.nasa.gov/

Information on each figure - and the data used in it, below.

##Figures
This directory includes scripts for figures where applicable, or otherwise states where the figure was created.
'* indicates script provided. All scripts are provided in this repository, except the Google Earth Engine script for Video S1, which is at the provided link.
If there is no script, it is because it was created 'manually'.

#FIG1
Created in QGIS (QGIS.org). Fig. 1a utilizes the free QGIS package 'Quantarctica' (https://www.npolar.no/en/quantarctica/) and 1b uses a MODIS image from https://worldview.earthdata.nasa.gov/

#FIG2
Created in QGIS. Figs. 1a-d use Sentinel-1 images downloaded from ASF (https://asf.alaska.edu/) and BedMachine v2 data from (https://nsidc.org/data/nsidc-0756)

#FIG3
Created in QGIS using Sentinel-1 image downloaded from ASF.

#FIG4*
Created in Python. Data from University of Bremen (https://seaice.uni-bremen.de/start/)

#FIG5*
Created in Python. Data from University of Bremen.

#FIG6*
Created in Python. Script provided. Ice production data processed from University of Bremen and ECMWF (cds.climate.copernicus.eu.) data as described in paper, following Cheng et al. 2017. Script also provided for processing.

#FIG7
Created in QGIS from data processed in Python.  Ice production data processed from University of Bremen and ECMWF data as described in paper, following Cheng et al. 2017. Script also provided for processing.

#FIG8*
Created in Python. Script provided. Data from University of Bremen and ECMWF.

#FIG9*
Created in Python. Script provided. Data from ECMWF.

#FIG10*
Created in Python. Script provided. Data from University of Bremen.

#FIG11
Created in QGIS.  Data from University of Bremen.

#FIGS1
Created in QGIS, uses a MODIS image from https://worldview.earthdata.nasa.gov/

#FIGS2*
Created in Python. Script provided. Data from University of Bremen and ECMWF.

#FIGS3*
Created in Python. Script provided. Ice production data processed from University of Bremen and ECMWF (cds.climate.copernicus.eu.) data as described in paper, following Cheng et al. 2017.

#FIGS4*
Created in Python. Script provided. Data from University of Bremen

#VIDEO S1*
Timel-lapse video created in multiple parts in Google Earth Engine (script: https://code.earthengine.google.com/3f291f9bedad1408ad8378eea52fdc15). 
Video then time-stamped in Python (Script provided) and stitched together using QuicktimePlayer.

#Video S2*
Created in Python. Script provided. Data from University of Bremen.

#Video S3*
Created in Python. Script provided. Data from ECMWF.

-----------

To calculate Iceproduction:
1) CalculateHeatFlux.ipynb
2) CalculateIceProduction.ipynb


-------------

Mask7.shp (and shx/dbf) = ASP study area shapefile

BroaderSICMask1.shp (and shx/dbf) = Broader ASP study area shapefile

