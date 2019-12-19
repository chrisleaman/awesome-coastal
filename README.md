# awesome-coastal
This is a list of resources which coastal engineers and scientists might find useful. Since we're a fairly niche discipline, it's often difficult to find out about all the great things out in the community! This list brings together useful data-sets, tools and scripts that people might not have been aware of.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
### Contents

  - [Contributing](#contributing)
- [By topic](#by-topic)
  - [Beach erosion](#beach-erosion)
  - [Wave modelling](#wave-modelling)
  - [Terrestial and UAV video analysis](#terrestial-and-uav-video-analysis)
  - [Satellite remote sensing](#satellite-remote-sensing)
  - [Early warning systems](#early-warning-systems)
- [By location](#by-location)
  - [Global](#global)
  - [Australia](#australia)
  - [New Zealand](#new-zealand)
  - [USA](#usa)
  - [Europe](#europe)
- [Community](#community)
- [Related lists](#related-lists)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

----

### Contributing
If you have any resources that could be useful for coastal engineers and scientists please let us know! This list is mainly focussed on data-sets and software packages that have been developed (and less so on listing papers, reports or books). Contributing can be done in one of two ways:

1. If you're comforatable with Github, make a [pull request](https://github.com/chrisleaman/awesome-coastal/pulls)
2. Or else, open a [new issue](https://github.com/chrisleaman/awesome-coastal/issues)
3. You pull request or issue should provide a link to a resource and a description of what it does and why it might be useful.

----

## By topic

### Beach erosion
- [TomasBeuzen/autobeach](https://github.com/TomasBeuzen/PH12_Dune_Erosion_Model): Python tool for automatically identifying beach profile features such as dune toes, dune crests, beach width and beach slopes.
- [TomasBeuzen/PH12_Dune_Erosion_Model](https://github.com/TomasBeuzen/PH12_Dune_Erosion_Model): Matlab and Python implementations of dune erosion models.
- [XBeach](https://oss.deltares.nl/web/xbeach/): Open sourced, processed-based model for beach and dune erosion.

### Wave modelling
- [chrisleaman/py-wave-runup](https://github.com/chrisleaman/py-wave-runup): Python package with many empirical wave runup equations for sandy beaches.
- [TomasBeuzen/BeuzenEtAl_GP_Paper](https://github.com/TomasBeuzen/BeuzenEtAl_GP_Paper): Python Juypter notebook demonstrating a Gauassian-Process machine learning implementation of wave runup prediction.
- [Power et al. (2018) runup data](https://www.sciencedirect.com/science/article/pii/S0378383918302552): 1391 wave runup records collated from a variety of sources.
- [Field Research Facility LiDAR Runup measurements](https://frfdataportal.erdc.dren.mil/): Wave runup measurements taken by the LiDAR at the FRF in North Carolina, USA.
- [SWASH](http://swash.sourceforge.net/): SWASH is a general-purpose numerical tool for simulating unsteady, non-hydrostatic, free-surface, rotational flow and transport phenomena in coastal waters as driven by waves, tides, buoyancy and wind forces.
- [umwm/umwm](https://github.com/umwm/umwm): Opensource code University of Miami Wave Model, a third-generation spectral ocean wave model.
- 🆕 [georgebv/coastlib](https://github.com/georgebv/coastlib): coastlib is a Python library dedicated to solving problems related to the discipline of coastal engineering, such as enivronmental data collection (NOAA CO-OPS and NCEI, and WAVEWATCH III, etc.), extreme value analysis (EVA), data analysis and visualization, wave theories, and many more.


### Terrestial and UAV video analysis
- [Coastal Imaging Research Network](https://github.com/Coastal-Imaging-Research-Network): The CIRN organisation provides toolboxes to estimate bathymetry from video (cBathy) taken from fixed ARGUS stations or UAVs. Repos include the cBathy toolbox, UAV processing toolbox and image calibration and rectification routines. Currently all code uses MATLAB.
- [CoastSnap](https://github.com/Coastal-Imaging-Research-Network/CoastSnap-Toolbox): MATLAB toolbox to extract shorelines from pictures of beaches taken by the global community. More info [here](https://www.environment.nsw.gov.au/research-and-publications/your-research/citizen-science/digital-projects/coastsnap) and [here](https://www.facebook.com/coastsnap/).
- [caiostringari/pywavelearn](https://oss.deltares.nl/web/xbeach/): pywavelearn provides a number of python scripts to process video of the swash zone. It provides functions to calibrate and rectify camera images, generate timestacks and classify pixels to track wave breaking.
- [simmonsja/cnn-shoreline-detect](https://github.com/simmonsja/cnn-shoreline-detect): Shoreline detection on oblique images of beaches using a HED CNN approach and Python.
- [dbuscombe-usgs/IR_waveclass](https://github.com/dbuscombe-usgs/IR_waveclass): Software and data for training deep convolutional neural network models to classify wave breaker type from IR images of breaking waves in the surf zone using Python. 
- 🆕 [rgerum/cameratransform](https://github.com/rgerum/cameratransform): Python package to fit camera properties and perform transformation from pixel to real-world coordinates and back again.
- 🆕 [conlin-matt/SurfRCaT](https://github.com/conlin-matt/SurfRCaT): Surf-Camera remote calibration tool that allows for the rectification of imagery from any coastal camera that views structures identifiable in lidar data.
- 🆕 [jonghyunharrylee/pyPCGA](https://github.com/jonghyunharrylee/pyPCGA/blob/master/examples/stwave_duck/inversion_stwave.ipynb): Example of bathymetric invesion using STWAVE.


### Satellite remote sensing
- [kvos/CoastSat](https://github.com/kvos/CoastSat): CoastSat is a python package which
  processes LandSat imagery (over 30 years available) and extracts shorelines using a sub-pixel resolution technique.
- [dbuscombe-usgs/EarthAnnotator](https://github.com/dbuscombe-usgs/EarthAnnotator): A tool for web-based image annotation and efficient labeling pixels in images using Python
- 🆕 [Subpixel_waterlines](https://github.com/GeoscienceAustralia/dea-notebooks/tree/subpixel_waterlines): Python code and Jupyter Notebooks for extracting sub-pixel resolution waterlines from large multidimensional satellite datasets (e.g. from Open Data Cube or Google Earth Engine)

### Early warning systems
- [Emilia-Romagna Storm Early Warning System](https://geo.regione.emilia-romagna.it/schede/ews/): Storm impact early warning system for the Italian coastline.
- [SWEEP OWWL](https://www.channelcoast.org/ccoresources/sweep/): Wave overtopping forecasting system for the southwest coast of the UK.


## By location

### Global
- [Aviso FES2014 Global Tide Database](https://www.aviso.altimetry.fr/en/data/products/auxiliary-products/global-tide-fes.html): Predicted tide elevations, currents and loadings on a 1/16 x 1/16 degree grid for anywhere in the world. Simple to use python interface provided at [cnes_aviso/fes](https://bitbucket.org/cnes_aviso/fes/src/master/).
- [WAVEWATCH III](https://polar.ncep.noaa.gov/waves/): Global wave model supplying hindcasts and forecasts around the world. Development has been recentl move to the open-source [NOAA-EMC/WW3](https://github.com/NOAA-EMC/WW3) repo.
- [fitnr/buoyant](https://github.com/fitnr/buoyant): Buoyant is a Python wrapper for grabbing buoy data from the National Buoy Data Center. It parses CSV from the SDF endpoint and images from the BuoyCam service.
- [ECMWF ERA5](https://confluence.ecmwf.int/display/CKB/ERA5+data+documentation): Global climiate reanalysis which includes ocean waves. ERA5 data released so far covers the period from 1979 to 2-3 months before the present.
- [Global Sea Level Observing System](https://www.psmsl.org/data/): Tide observations from a global network of gauges. 
- 🆕 [Global Extreme Sea Level Analysis](https://www.gesla.org/): Worldwide dataset of frequency and magnitude of extreme sea levels.
- 🆕 [GEBCO global bathymetry](https://www.gebco.net/data_and_products/gridded_bathymetry_data/): Global terrain model for ocean and land at 15 arc-second intervals.
- 🆕 [OpenCoastS](https://opencoasts.ncg.ingrid.pt/): On-demand ocean forecasting system for coastal areas providing water levels, velocities and wave parameters.
- 🆕 [MERIT DEM](http://hydro.iis.u-tokyo.ac.jp/~yamadai/MERIT_DEM/): Improved global DEM at 3 arc-second resolution.
- 🆕 [CoastalDEM](https://go.climatecentral.org/coastaldem/): Global DEM with improved error correction around coastal areas.


### Australia
- [Narrabeen-Collaroy Beach Survey Program](http://narrabeen.wrl.unsw.edu.au/): Long-term data set (40+ years) of beach profiles at Narrabeen-Collaroy (Sydney Northern Beaches).
- [NSW Neashore Wave Transfomation toolbox](http://www.nswaves.com.au/help_toolbox.php): Tools to transform offshore wave contours to 10m and 30m depth contour. Can provide historic nearshore wave conditions based on WaveRider buoys and WaveWatch 3 data from 1980.
- [Geoscience Australia Intertidal DEM (NIDEM) and High/Low Tide Composites](https://nationalmap.gov.au/): DEM and satellite composite images at low and high tide for entire Australian coastline. (Click `Explore data` -> `Marine and Oceans` -> `Coastal`).
- 🆕 [AusSeabed Marine Data Discovery](https://marine.ga.gov.au/#/): Geoscience Australia’s marine data discovery interface for coastal and seafloor mapping products (e.g. bathymetry, backscatter and sidescan sonar data etc)
- [Coastal Sediment Compartments](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/87838): The entire Australian shoreline broken up into primary, secondary and tertiary sediment comparments.
- [Smartline](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata104160): Geomorphology data provided for the entire Australian shoreline.
- [Coastal Risk Australia](http://coastalrisk.com.au): Maps of predicted coastal flooding resulting from climate change
- [NSW Beach Profile Database](http://www.nswbpd.wrl.unsw.edu.au/): Beach profiles from 150 locations along the NSW Coast, from as far north as Tweed Heads and to as far south as Eden. Data available for download.
- 🆕 [Australian Ocean Data Network](https://portal.aodn.org.au/search): The AODN Portal provides access to all available Australian marine and climate science data.
- 🆕 [CAWCR Wave Hindcast](https://data.csiro.au/collections/#collection/CIcsiro:39819/BTkw/BVwave/RP1/RS25/RORELEVANCE/STnull/RI1/RT4/): WaveWatch III hindcast with high resolutions in the Western Pacific and Australian regions. Hindcast dates available from 1979 to 2014.
- 🆕 [Extreme Sea Levels in Australia](http://sealevelx.ems.uwa.edu.au/): Present day extreme sea level statistics around Australia.

### New Zealand
- 🆕 [NZ Storm Surge Hindcast](https://uoa-eresearch.github.io/storm_surge/#Model_20CR@1871-01-01): Hindcast of NZ storm surge at 0.25 degrees.

### USA
- [Field Research Facility, Duck NC](https://frfdataportal.erdc.dren.mil/): Long term monitoring and extensive field campaigns with geomorphology, meteorology, oceanography data sets available for download.
- [San Diego beach dataset](https://www.nature.com/articles/s41597-019-0167-6): Beach profiles and wave conditions at three southern California beaches during 2001-2016. (Ludka et al, 2019)
- 🆕 [SECOORA Data Portal](https://portal.secoora.org/): Centralized access to Southeast U.S. coastal and ocean data.


### Europe
- [Channel Coast Observatory](https://www.channelcoast.org/ccoresources/): Beach profiles, wave and tide data, model predictions for several sites around the UK.
- 🆕 [Ruessink et al, 2019](https://zenodo.org/record/2635416): A multi-year data set of beach-foredune topography and environmental forcing conditions at Egmond aan Zee, the Netherlands.


## Community
- [Coastal List](https://groups.google.com/a/udel.edu/forum/#!categories/coastal_list): Possibly the largest coastal engineer/scientist mailing list with over 6800 subscribers. Run by the University of Delware, job ads, student opportunities, workshops, training courses and conferences are all posted here.
- 🆕 [Earth science jobs list](https://docs.google.com/spreadsheets/d/1-i6zRM8aQnLswnpQOmqUZ3zqzph9L7hg5kccIkqiA80/edit#gid=989950331): Google spreadsheet of list of available earth science faculty jobs.


## Related lists
- [Awesome-Spatial](https://github.com/RoboDonut/awesome-spatial): Awesome list for geospatial.
- [Awesome Open Geoscience](https://github.com/softwareunderground/awesome-open-geoscience): Awesome list for open-source geoscience. Items lean towards subsurface geoscience but significant overlap with coastal geoscience.
- [Awesome Open Climate Science](https://github.com/pangeo-data/awesome-open-climate-science): Awesome list for atmospheric, ocean, aWnd climate sciences.
- 🆕 [SpatialPoints.com Useful Resources](http://www.spatialpoints.com/category/resources/): The Spatial Sciences Group at The University of Adelaide's list of useful resources.

