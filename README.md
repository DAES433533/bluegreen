# Examining Hurricane Helene Meteorological History, Physical Impacts, Emergency Management Details, and Social Impacts

<img src="thumbnails/thumbnail.png" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

_See the [Cookbook Contributor's Guide](https://projectpythia.org/cookbook-guide) for step-by-step instructions on how to create your new Cookbook and get it hosted on the [Pythia Cookbook Gallery](https://cookbooks.projectpythia.org)!_

This Project Pythia Cookbook robustly explores different facets of Hurricane Helene. This cookbook includes notebooks examining the rapid intensification, landfall, and extratropical transition; meteorological details covering central pressure and wind speed; physical impacts such as storm surge, tornadoes, flooding, and landslides; and social consequences discussing emergency management responses, infrastructure impacts, and social vulnerability.

## Motivation

Hurricane Helene was a Category 4 tropical cyclone that made landfall in September 2024. Different states across the United States suffered the impacts of this catastrophic hurricane. The two notebooks, Helene_Genesis_To_Intensification and Helene_Florida_Impacts, examine Hurricane Helene from its early development to landfall, through ERA5 reanalysis, IBTrACS data, storm surge tide gauge observations, and a geographic dataset. The environmental conditions that supported Helene’s rapid intensification, including sea surface temperatures, vertical wind shear, and upper-level flow patterns, were analyzed to evaluate the storm’s accurate track predictions and steady intensification. Then, its impact on Florida’s Gulf Coast was assessed by mapping storm surge against coastal bathymetry and known inundation-prone regions. Together, these analyses link Helene’s genesis and intensification to its coastal hazards and highlight the storm surge vulnerability on the Gulf Coast of Florida. Helene impacted inland regions much more dramatically with flooding, but its deadly impacts on the Florida coastline cannot be overlooked or forgotten either. The tropical Python module was used as part of the landfall and postlandfall of Hurricane Helene. The Helene_Landfall_1 examines the HURDAT2 data, forecast information, and tornado reports. Tropical resulted as a very useful tool. The results show that Helene weakened rapidly after crossing the Florida Big Bend and that most tornado activity occurred east of the storm’s center. On the other hand, the Helene_Landfall_2 focuses on the post-tropical phase, during which the system stalled over Tennessee and interacted with a nearby extratropical cyclone through a Fujiwhara Effect. By combining HURDAT2, ERA5 geopotential fields, TempestExtremes, CPyS, the analysis demonstrated that Helene transitioned from a warm-core system to a cold-core system sometime between 0600 UTC and 1200 UTC on September 28th, 2024. This indicates when the system became post-tropical, where it proceeded to stall over the Southeastern U.S. and experience the Fujiwhara Effect with another extratropical cyclone in the region. The heavy rainfall triggered widespread flooding and landslides across the Appalachian Mountains. The helene_flooding and helene_landslides notebooks help visualize the relationships between rainfall, river discharge, and mass movements in North Carolina. Multiple visualizations were produced to better understand these connections. At the two selected river sites within the mountain chain, the gage height increased at the same time discharge peaked, indicating that flooding was occurring at those locations, peaking on September 28, after the rainfall events. Meanwhile, the helene_landslides notebook shows that most landslides were concentrated near the mountain range, highlighting the relationship between steep slopes and mass movement processes. As a result of the impacts caused by Hurricane Helene, presidential disaster declarations were issued. The helene_emergency_impacts and helene_social_vulnerability examine the emergency management process after Hurricane Helene hit, as well as the social vulnerability of the places most impacted, such as in the Appalachian Mountains. Utilizing Hurricane Helene Recovery Data from the U.S. Census Bureau’s Assessment, Recovery, and Evaluation datasets and Census Data, maps were created to show the extent of Hurricane Helene's damage and the emergency management declarations and recovery program assistance registrations issued as a result. Spatial relationships between variables were also examined, analyzing connections between power outages, wind swaths, and precipitation. Social vulnerability factors were plotted as well to provide essential contextual details on the severity of the impacts caused by Hurricane Helene.

## Authors

[Alejandra Garcia](https://github.com/alegarcia1417), [Anna Walker](https://github.com/jwalk618), [Bianca Mendez Cruz](https://github.com/BiancaV247), [Thomas Weist](https://github.com/tweist27)

## Structure

This Cookbook is broken up into four main sections: Helene Development and Coastal Impacts, Helene Landfall/Extra-Tropical Transition and Inland Impacts, Helene Flooding and Landslides, and Helene Emergency Management and Social Impacts.

### Helene Development and Coastal Impacts

This section includes notebooks Helene_Genesis_To_Intensification and Helene_Florida_Impacts. The notebooks within this section explore the early development, rapid intensification, and storm surge/coastal impacts upon initial landfall of Hurricane Helene in Florida. Through the use of ERA5 reanalysis data, NHC best-track observations (IBTrACS), and NOAA Center for Operational Oceanographic Products and Services (CO-OPS) dataset, these notebooks analyze and visualize variables not limited to sea surface temperature, upper-level winds, storm structure/motion, landfall timeline, wind field structure, storm surge, and flood risk.

### Helene Landfall/Extra-Tropical Transition and Inland Impacts

This section includes notebooks Helene_Landfall_1 and Helene_Landfall_2. The notebooks within this section explore Helene's landfall, wind and tornado impacts, transition into an extratropical cyclone, stalling over Tennessee, and subsequent physical impacts due to the stall. Through the use of ERA5 reanalysis data and Atlantic hurricane database (HURDAT2), as well as modules and features such as Tropycal Python module and TempestExtremes' NodeFileCompose, variables such as Helene forecast information, wind and pressure data, tornado data, geopotential height, and cyclone phase were visualized and examined.  

### Helene Flooding and Landslides

This section includes notebooks helene_flooding and helene_landslides. The notebooks within this section look at the result of Hurricane Helene's rainfall in regards to river discharge, topography, soil moisture, flooding, and landslides. Through the use of datasets such as the U.S. Army Corps of Engineers, Nashville District Hurricane Helene Flood Data Collection, United States Geological Survey (USGS) Water Data Website, and U.S. Department of the Interior Preliminary Landslide Inventory, these notebooks visualize and analyze precipitation, hydrological features, contributions to flooding hazards, and terrain.

### Helene Emergency Management and Social Impacts

This section includes notebooks helene_emergency_impacts and helene_social_vulnerability. The notebooks within this section examine the emergency management response to Hurricane Helene by looking at presidential disaster declarations, FEMA recovery assistance programs, and physical impacts caused by Hurricane Helene, such as power outages, wind swaths, and precipitation. Socioeconomic factors, rurality, age, and other social vulnerability variables were also analyzed and plotted geographically through the use of the Hurricane Helene Recovery Data from the U.S. Census Bureau’s Assessment, Recovery, and Evaluation datasets and Census Data.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/helene_cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/helene_cookbook.git
   ```

1. Move into the `helene_cookbook` directory
   ```bash
   cd helene_cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate helene_cookbook
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
