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
- [Related Awesome](#related-awesome)
- [By location](#by-location)
  - [Global](#global)
  - [Australia](#australia)
  - [USA](#usa)
  - [UK](#uk)
- [Community](#community)
  - [Mailing lists](#mailing-lists)

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


### Terrestial and UAV video analysis
- [Coastal Imaging Research Network](https://github.com/Coastal-Imaging-Research-Network): The CIRN organisation provides toolboxes to estimate bathymetry from video (cBathy) taken from fixed ARGUS stations or UAVs. Repos include the cBathy toolbox, UAV processing toolbox and image calibration and rectification routines. Currently all code uses MATLAB.
- [CoastSnap](https://github.com/Coastal-Imaging-Research-Network/CoastSnap-Toolbox): MATLAB toolbox to extract shorelines from pictures of beaches taken by the global community. More info [here](https://www.environment.nsw.gov.au/research-and-publications/your-research/citizen-science/digital-projects/coastsnap) and [here](https://www.facebook.com/coastsnap/).
- [caiostringari/pywavelearn](https://oss.deltares.nl/web/xbeach/): pywavelearn provides a number of python scripts to process video of the swash zone. It provides functions to calibrate and rectify camera images, generate timestacks and classify pixels to track wave breaking.
- [simmonsja/cnn-shoreline-detect](https://github.com/simmonsja/cnn-shoreline-detect): Shoreline detection on oblique images of beaches using a HED CNN approach and Python.
- [dbuscombe-usgs/IR_waveclass](https://github.com/dbuscombe-usgs/IR_waveclass): Software and data for training deep convolutional neural network models to classify wave breaker type from IR images of breaking waves in the surf zone using Python. 


### Satellite remote sensing
- [kvos/CoastSat](https://github.com/kvos/CoastSat): CoastSat is a python package which
  processes LandSat imagery (over 30 years available) and extracts shorelines using a sub-pixel resolution technique.
- [dbuscombe-usgs/EarthAnnotator](https://github.com/dbuscombe-usgs/EarthAnnotator): A tool for web-based image annotation and efficient labeling pixels in images using Python

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

### Australia
- [Narrabeen-Collaroy Beach Survey Program](http://narrabeen.wrl.unsw.edu.au/): Long-term data set (40+ years) of beach profiles at Narrabeen-Collaroy (Sydney Northern Beaches).
- [NSW Neashore Wave Transfomation toolbox](http://www.nswaves.com.au/help_toolbox.php): Tools to transform offshore wave contours to 10m and 30m depth contour. Can provide historic nearshore wave conditions based on WaveRider buoys and WaveWatch 3 data from 1980.
- [Geoscience Australia Intertidal DEM and Composites](https://nationalmap.gov.au/): DEM and satellite composite images for entire Australian coastline. (Click `Add data` -> `Surface Water and Marine` -> `Tidal`).
- [Coastal Sediment Compartments](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/87838): The entire Australian shoreline broken up into primary, secondary and tertiary sediment comparments.
- [Smartline][(https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata104160): Geomorphology data provided for the entire Australian shoreline.
- [Coastal Risk Australia](http://coastalrisk.com.au): Maps of predicted coastal flooding resulting from climate change
- [NSW Beach Profile Database](http://www.nswbpd.wrl.unsw.edu.au/): Beach profiles from 150 locations along the NSW Coast, from as far north as Tweed Heads and to as far south as Eden. Data available for download.

### USA
- [Field Research Facility, Duck NC](https://frfdataportal.erdc.dren.mil/): Long term monitoring and extensive field campaigns with geomorphology, meteorology, oceanography data sets available for download.
- [San Diego beach dataset](https://www.nature.com/articles/s41597-019-0167-6): Beach profiles and wave conditions at three southern California beaches during 2001-2016. (Ludka et al, 2019)


### UK
- [Channel Coast Observatory](https://www.channelcoast.org/ccoresources/): Beach profiles, wave and tide data, model predictions for several sites around the UK.


## Community

### Mailing lists
- [Coastal List](https://groups.google.com/a/udel.edu/forum/#!categories/coastal_list):
  Possibly the largest coastal engineer/scientist mailing list with over 6800 subscribers. Run by the University of Delware, job ads, student opportunities, workshops, training courses and conferences are all posted here.


## Related awesome lists
- [Awesome-Spatial](https://github.com/RoboDonut/awesome-spatial): Awesome list for geospatial.
- [Awesome Open Geoscience](https://github.com/softwareunderground/awesome-open-geoscience): Awesome list for open-source geoscience. Items lean towards subsurface geoscience but significant overlap with coastal geoscience.
- [Awesome Open Climate Science](https://github.com/pangeo-data/awesome-open-climate-science): Awesome list for atmospheric, ocean, aWnd climate sciences.

