# awesome-coastal
This is a list of resources which coastal engineers and scientists might find useful. Since we're a fairly niche discipline, it's often difficult to find out about all the great things out in the community! This list brings together useful data-sets, tools and scripts that people might not have been aware of.


### Contents
  - [Tools, software, scripts and packages](#tools-software-scripts-and-packages)
    - [Beach erosion](#beach-erosion)
    - [Wave runup](#wave-runup)
    - [Terrestial and UAV video analysis](#terrestial-and-uav-video-analysis)
    - [Satellite imaging](#satellite-imaging)
  - [Data](#data)
    - [Global](#global)
    - [Australia](#australia)
  - [Community](#community)
    - [Mailing lists](#mailing-lists)

----

### Contributing
If you have any resources that could be useful for coastal engineers and scientists please let us know! This list is mainly focussed on data-sets and software packages that have been developed (and less so on listing papers, reports or books). Contributing can be done in one of two ways:

1. If you're comforatable with Github, make a [pull request](https://github.com/chrisleaman/awesome-coastal/pulls)
2. Or else, open a [new issue](https://github.com/chrisleaman/awesome-coastal/issues)

You pull request or issue should provide a link to a resource and a description of what it does and why it might be useful.

----

## Tools, software, scripts and packages

### Beach erosion
- [TomasBeuzen/autobeach](https://github.com/TomasBeuzen/autobeach): Python tool for automatically identifying beach profile features such as dune toes, dune crests, beach width and beach slopes.
- [TomasBeuzen/PH12_Dune_Erosion_Model](https://github.com/TomasBeuzen/PH12_Dune_Erosion_Model): Matlab and Python implementations of dune erosion models.

### Wave runup
- [chrisleaman/py-wave-runup](https://github.com/chrisleaman/py-wave-runup): Python package with many empirical wave runup equations for sandy beaches.
- [TomasBeuzen/BeuzenEtAl_GP_Paper](TomasBeuzen/BeuzenEtAl_GP_Paper): Python Juypter notebook demonstrating a Gauassian-Process machine learning implementation of wave runup prediction.

### Terrestial and UAV video analysis
- [Coastal Imaging Research Network](https://github.com/Coastal-Imaging-Research-Network): The CIRN organisation provides toolboxes to estimate bathymetry from video (cBathy) taken from fixed ARGUS stations or UAVs. Repos include the cBathy toolbox, UAV processing toolbox and image calibration and rectification routines. Currently all code uses MATLAB.
- [caiostringari/pywavelearn](https://github.com/caiostringari/pywavelearn): pywavelearn provides a number of python scripts to process video of the swash zone. It provides functions to calibrate and rectify camera images, generate timestacks and classify pixels to track wave breaking.


### Satellite imaging
- [kvos/CoastSat](https://github.com/kvos/CoastSat): CoastSat is a python package which processes LandSat imagery (over 30 years available) and extracts shorelines using a sub-pixel resolution technique.


## Data

### Global
- [Aviso FES2014 Global Tide Database](https://www.aviso.altimetry.fr/en/data/products/auxiliary-products/global-tide-fes.html): Predicted tide elevations, currents and loadings on a 1/16 x 1/16 degree grid for anywhere in the world. Simple to use python interface provided at [cnes_aviso/fes](https://bitbucket.org/cnes_aviso/fes/src/master/).


### Australia
- [Narrabeen-Collaroy Beach Survey Program](http://narrabeen.wrl.unsw.edu.au/): Long-term data set (40+ years) of beach profiles at Narrabeen-Collaroy (Sydney Northern Beaches).
- [NSW Neashore Wave Transfomation toolbox](http://www.nswaves.com.au/help_toolbox.php): Tools to transform offshore wave contours to 10m and 30m depth contour. Can provide historic nearshore wave conditions based on WaveRider buoys and WaveWatch 3 data from 1980.
- [Geoscience Australia Intertidal DEM and Composites](https://nationalmap.gov.au/): DEM and satellite composite images for entire Australian coastline. (Click "Add data" -> "Surface Water and Marine" -> "Tidal").
- [Coastal Sediment Compartments](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/87838): The entire Australian shoreline broken up into primary, secondary and tertiary sediment comparments.
- [Smartline](https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/104160): Geomorphology data provided for the entire Australian shoreline.


## Community

### Mailing lists
- [Coastal List](https://groups.google.com/a/udel.edu/forum/#!categories/coastal_list): Possibly the largest coastal engineer/scientist mailing list with over 6800 subscribers. Run by the University of Delware, job ads, student opportunities, workshops, training courses and conferences are all posted here. 