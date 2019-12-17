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
- [TomasBeuzen/autobeach][autobeach] Python tool for automatically identifying beach profile features such as dune toes, dune crests, beach width and beach slopes.
- [TomasBeuzen/PH12_Dune_Erosion_Model][ph12]: Matlab and Python implementations of dune erosion models.
- [XBeach][xbeach]: Open sourced, processed-based model for beach and dune erosion.

  [autobeach]: https://github.com/TomasBeuzen/PH12_Dune_Erosion_Model
  [ph12]: https://github.com/TomasBeuzen/PH12_Dune_Erosion_Model
  [xbeach]: https://oss.deltares.nl/web/xbeach/

### Wave modelling
- [chrisleaman/py-wave-runup][pywaverunup]: Python package with many empirical wave runup equations for sandy beaches.
- [TomasBeuzen/BeuzenEtAl_GP_Paper][gaus-process]: Python Juypter notebook demonstrating a Gauassian-Process machine learning implementation of wave runup prediction.
- [Power et al. (2018) runup data][power]: 1391 wave runup records collated from a variety of sources.
- [Field Research Facility LiDAR Runup measurements][frf]: Wave runup measurements taken by the LiDAR at the FRF in North Carolina, USA.
- [SWASH][swash]: SWASH is a general-purpose numerical tool for simulating unsteady, non-hydrostatic, free-surface, rotational flow and transport phenomena in coastal waters as driven by waves, tides, buoyancy and wind forces.
- [umwm/umwm][umwm]: Opensource code University of Miami Wave Model, a third-generation spectral ocean wave model.

  [power]: https://www.sciencedirect.com/science/article/pii/S0378383918302552
  [frf]: https://frfdataportal.erdc.dren.mil/
  [pywaverunup]: https://github.com/chrisleaman/py-wave-runup
  [gaus-process]: https://github.com/TomasBeuzen/BeuzenEtAl_GP_Paper
  [swash]: http://swash.sourceforge.net/
  [umwm]: https://github.com/umwm/umwm

### Terrestial and UAV video analysis
- [Coastal Imaging Research Network][cirn]: The CIRN organisation provides toolboxes to estimate bathymetry from video (cBathy) taken from fixed ARGUS stations or UAVs. Repos include the cBathy toolbox, UAV processing toolbox and image calibration and rectification routines. Currently all code uses MATLAB.
- [CoastSnap][coastsnap]: MATLAB toolbox to extract shorelines from pictures of beaches taken by the global community. More info [here][coastsnap1] and [here][coastsnap2].
- [caiostringari/pywavelearn][pywavelearn]: pywavelearn provides a number of python scripts to process video of the swash zone. It provides functions to calibrate and rectify camera images, generate timestacks and classify pixels to track wave breaking.
- [simmonsja/cnn-shoreline-detect][cnn-shoreline-detect]: Shoreline detection on oblique images of beaches using a HED CNN approach and Python.
- [dbuscombe-usgs/IR_waveclass][IR_waveclass]: Software and data for training deep convolutional neural network models to classify wave breaker type from IR images of breaking waves in the surf zone using Python.

  [cirn]: https://github.com/Coastal-Imaging-Research-Network
  [pywavelearn]: https://oss.deltares.nl/web/xbeach/
  [cnn-shoreline-detect]: https://github.com/simmonsja/cnn-shoreline-detect
  [IR_waveclass]: https://github.com/dbuscombe-usgs/IR_waveclass
  [coastsnap]: https://github.com/Coastal-Imaging-Research-Network/CoastSnap-Toolbox
  [coastsnap1]: https://www.environment.nsw.gov.au/research-and-publications/your-research/citizen-science/digital-projects/coastsnap
  [coastsnap2]: https://www.facebook.com/coastsnap/


### Satellite remote sensing
- [kvos/CoastSat][coastsat]: CoastSat is a python package which
  processes LandSat imagery (over 30 years available) and extracts shorelines using a sub-pixel resolution technique.
- [dbuscombe-usgs/EarthAnnotator][EarthAnnotator]: A tool for web-based image annotation and efficient labeling pixels in images using Python

  [coastsat]: https://github.com/kvos/CoastSat
  [EarthAnnotator]: https://github.com/dbuscombe-usgs/EarthAnnotator

### Early warning systems
- [Emilia-Romagna Storm Early Warning System][emilia-romagna]: Storm impact early warning system for the Italian coastline.
- [SWEEP OWWL][sweep-owwl]: Wave overtopping forecasting system for the southwest coast of the UK.

  [emilia-romagna]: https://geo.regione.emilia-romagna.it/schede/ews/
  [sweep-owwl]: https://www.channelcoast.org/ccoresources/sweep/

## Related Awesome
- [Awesome-Spatial][awesome-spatial]: Awesome list for geospatial.
- [Awesome Open Geoscience][awesome-geoscience]: Awesome list for open-source geoscience. Items lean towards subsurface geoscience but significant overlap with coastal geoscience.
- [Awesome Open Climate Science][awesome-climate]: Awesome list for atmospheric, ocean, aWnd climate sciences.

  [awesome-spatial]: https://github.com/RoboDonut/awesome-spatial
  [awesome-geoscience]: https://github.com/softwareunderground/awesome-open-geoscience
  [awesome-climate]: https://github.com/pangeo-data/awesome-open-climate-science

## By location

### Global
- [Aviso FES2014 Global Tide Database][aviso]: Predicted tide elevations, currents and loadings on a 1/16 x 1/16 degree grid for anywhere in the world. Simple to use python interface provided at [cnes_aviso/fes][aviso-fes].
- [WAVEWATCH III][ww3]: Global wave model supplying hindcasts and forecasts around the world. Development has been recentl move to the open-source [NOAA-EMC/WW3][ww3-github] repo.
- [fitnr/buoyant][buoyant]: Buoyant is a Python wrapper for grabbing buoy data from the National Buoy Data Center. It parses CSV from the SDF endpoint and images from the BuoyCam service.
- [ECMWF ERA5][era5]: Global climiate reanalysis which includes ocean waves. ERA5 data released so far covers the period from 1979 to 2-3 months before the present.
- [Global Sea Level Observing System][gloss]: Tide observations from a global network of gauges. 

  [aviso]: https://www.aviso.altimetry.fr/en/data/products/auxiliary-products/global-tide-fes.html
  [aviso-fes]: https://bitbucket.org/cnes_aviso/fes/src/master/
  [ww3]: https://polar.ncep.noaa.gov/waves/
  [ww3-github]: https://github.com/NOAA-EMC/WW3
  [buoyant]: https://github.com/fitnr/buoyant
  [era5]: https://confluence.ecmwf.int/display/CKB/ERA5+data+documentation
  [gloss]: https://www.psmsl.org/data/

### Australia
- [Narrabeen-Collaroy Beach Survey Program][narrabeen]: Long-term data set (40+ years) of beach profiles at Narrabeen-Collaroy (Sydney Northern Beaches).
- [NSW Neashore Wave Transfomation toolbox][nsw-nearshore]: Tools to transform offshore wave contours to 10m and 30m depth contour. Can provide historic nearshore wave conditions based on WaveRider buoys and WaveWatch 3 data from 1980.
- [Geoscience Australia Intertidal DEM and Composites][intertidal-dem]: DEM and satellite composite images for entire Australian coastline. (Click `Add data` -> `Surface Water and Marine` -> `Tidal`).
- [Coastal Sediment Compartments][sediment-compartments]: The entire Australian shoreline broken up into primary, secondary and tertiary sediment comparments.
- [Smartline][smartline]: Geomorphology data provided for the entire Australian shoreline.
- [Coastal Risk Australia][coastal-risk-aus]: Maps of predicted coastal flooding resulting from climate change
- [NSW Beach Profile Database][nsw-beach-profiles]: Beach profiles from 150 locations along the NSW Coast, from as far north as Tweed Heads and to as far south as Eden. Data available for download.

  [narrabeen]: http://narrabeen.wrl.unsw.edu.au/
  [nsw-nearshore]: http://www.nswaves.com.au/help_toolbox.php
  [intertidal-dem]: https://nationalmap.gov.au/
  [sediment-compartments]: https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/87838
  [smartline]: https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/104160
  [coastal-risk-aus]: http://coastalrisk.com.au
  [nsw-beach-profiles]: http://www.nswbpd.wrl.unsw.edu.au/

### USA
- [Field Research Facility, Duck NC][frf]: Long term monitoring and extensive field campaigns with geomorphology, meteorology, oceanography data sets available for download.
- [San Diego beach dataset][sandiego]: Beach profiles and wave conditions at three southern California beaches during 2001-2016. (Ludka et al, 2019)

  [frf]: https://frfdataportal.erdc.dren.mil/
  [sandiego]: https://www.nature.com/articles/s41597-019-0167-6


### UK
- [Channel Coast Observatory][channel-coast]: Beach profiles, wave and tide data, model predictions for several sites around the UK.

  [channel-coast]: https://www.channelcoast.org/ccoresources/

## Community

### Mailing lists
- [Coastal List][coastal-list]:
  Possibly the largest coastal engineer/scientist mailing list with over 6800 subscribers. Run by the University of Delware, job ads, student opportunities, workshops, training courses and conferences are all posted here.

  [coastal-list]: https://groups.google.com/a/udel.edu/forum/#!categories/coastal_list
