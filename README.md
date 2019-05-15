# awesome-coastal
This is a list of resources which coastal engineers and scientists might find useful.
Since we're a fairly niche discipline, it's often difficult to find out about all the
great things out in the community! This list brings together useful data-sets, tools and
scripts that people might not have been aware of.


### Contents
  - [By topic](#by-topic)
    - [Beach erosion](#beach-erosion)
    - [Wave runup](#wave-runup)
    - [Terrestial and UAV video analysis](#terrestial-and-uav-video-analysis)
    - [Satellite imaging](#satellite-imaging)
  - [By location](#by-location)
    - [Global](#global)
    - [Australia](#australia)
    - [USA](#usa)
  - [Community](#community)
    - [Mailing lists](#mailing-lists)

----

### Contributing
If you have any resources that could be useful for coastal engineers and scientists
please let us know! This list is mainly focussed on data-sets and software packages that
have been developed (and less so on listing papers, reports or books). Contributing can
be done in one of two ways:

1. If you're comforatable with Github, make a [pull
   request](https://github.com/chrisleaman/awesome-coastal/pulls)
2. Or else, open a [new issue](https://github.com/chrisleaman/awesome-coastal/issues)

You pull request or issue should provide a link to a resource and a description of what
it does and why it might be useful.

----

## By topic

### Beach erosion
- [TomasBeuzen/autobeach][autobeach] Python tool for
  automatically identifying beach profile features such as dune toes, dune crests, beach
  width and beach slopes.
- [TomasBeuzen/PH12_Dune_Erosion_Model][ph12]:
  Matlab and Python implementations of dune erosion models.
- [XBeach][xbeach]: Open sourced, processed-based model for beach and dune erosion.

  [autobeach]: https://github.com/TomasBeuzen/PH12_Dune_Erosion_Model
  [ph12]: https://github.com/TomasBeuzen/PH12_Dune_Erosion_Model
  [xbeach]: https://oss.deltares.nl/web/xbeach/

### Wave runup
- [chrisleaman/py-wave-runup][pywaverunup]: Python package with many empirical wave
  runup equations for sandy beaches.
- [TomasBeuzen/BeuzenEtAl_GP_Paper][gaus-process]: Python Juypter notebook demonstrating
  a Gauassian-Process machine learning implementation of wave runup prediction.
- [Power et al. (2018) runup data][power]: 1391 wave runup records collated from a
  variety of sources.
- [Field Research Facility LiDAR Runup measurements][frf]: Wave runup measurements taken
  by the LiDAR at the FRF in North Carolina, USA.

  [power]: https://www.sciencedirect.com/science/article/pii/S0378383918302552
  [frf]: https://frfdataportal.erdc.dren.mil/
  [pywaverunup]: https://github.com/chrisleaman/py-wave-runup
  [gaus-process]: https://github.com/TomasBeuzen/BeuzenEtAl_GP_Paper

### Terrestial and UAV video analysis
- [Coastal Imaging Research Network][cirn](: The CIRN organisation provides toolboxes to
  estimate bathymetry from video (cBathy) taken from fixed ARGUS stations or UAVs. Repos
  include the cBathy toolbox, UAV processing toolbox and image calibration and
  rectification routines. Currently all code uses MATLAB.
- [caiostringari/pywavelearn][pywavelearn]: pywavelearn provides a number of python
  scripts to process video of the swash zone. It provides functions to calibrate and
  rectify camera images, generate timestacks and classify pixels to track wave breaking.

  [cirn]: https://github.com/Coastal-Imaging-Research-Network
  [pywavelearn]: https://oss.deltares.nl/web/xbeach/


### Satellite imaging
- [kvos/CoastSat][coastsat]: CoastSat is a python package which
  processes LandSat imagery (over 30 years available) and extracts shorelines using a
  sub-pixel resolution technique.

  [coastsat]: https://github.com/kvos/CoastSat


## By location

### Global
- [Aviso FES2014 Global Tide Database][aviso]: Predicted tide elevations, currents and
  loadings on a 1/16 x 1/16 degree grid for anywhere in the world. Simple to use python
  interface provided at [cnes_aviso/fes][aviso-fes].
- [WAVEWATCH III][ww3]: Global wave model supplying hindcasts and forecasts around the
  world. Development has been recentl move to the open-source [NOAA-EMC/WW3][ww3-github]
  repo.

  [aviso]: https://www.aviso.altimetry.fr/en/data/products/auxiliary-products/global-tide-fes.html
  [aviso-fes]: https://bitbucket.org/cnes_aviso/fes/src/master/
  [ww3]: https://polar.ncep.noaa.gov/waves/
  [ww3-github]: https://github.com/NOAA-EMC/WW3

### Australia
- [Narrabeen-Collaroy Beach Survey Program][narrabeen]: Long-term data set (40+ years)
  of beach profiles at Narrabeen-Collaroy (Sydney Northern Beaches).
- [NSW Neashore Wave Transfomation toolbox][nsw-nearshore]: Tools to transform offshore
  wave contours to 10m and 30m depth contour. Can provide historic nearshore wave
  conditions based on WaveRider buoys and WaveWatch 3 data from 1980.
- [Geoscience Australia Intertidal DEM and Composites][intertidal-dem]: DEM and
  satellite composite images for entire Australian coastline. (Click `Add data` ->
  `Surface Water and Marine` -> `Tidal`).
- [Coastal Sediment Compartments][sediment-compartments]: The entire Australian
  shoreline broken up into primary, secondary and tertiary sediment comparments.
- [Smartline][smartline]: Geomorphology data provided for the entire Australian
  shoreline.

  [narrabeen]: http://narrabeen.wrl.unsw.edu.au/
  [nsw-nearshore]: http://www.nswaves.com.au/help_toolbox.php
  [intertidal-dem]: https://nationalmap.gov.au/
  [sediment-compartments]: https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/87838
  [smartline]: https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/104160

### USA
- [Field Research Facility, Duck NC][frf]: Long term monitoring and extensive field
  campaigns with geomorphology, meteorology, oceanography data sets available for
  download.

  [frf]: https://frfdataportal.erdc.dren.mil/


## Community

### Mailing lists
- [Coastal List][coastal-list]:
  Possibly the largest coastal engineer/scientist mailing list with over 6800
  subscribers. Run by the University of Delware, job ads, student opportunities,
  workshops, training courses and conferences are all posted here.

  [coastal-list]: https://groups.google.com/a/udel.edu/forum/#!categories/coastal_list
