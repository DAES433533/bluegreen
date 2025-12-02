# Anna

This notebook explores the early development and rapid intensification of Hurricane Helene (2024).  
Using ERA5 reanalysis data and NHC best-track observations, we analyze the environmental factors that supported Helene’s strengthening as it moved across the Atlantic.

1. Retrieve and visualize Helene’s best-track from IBTrACS and plot the Sea Surface Temperatures (SSTs)
2. Plot 850 to 200hPa deep layer steering flow and 200hPa winds/jetstream from ERA5  
3. Examine the vertical structure and steering flow influencing storm motion  
4. Identify conditions favorable for rapid intensification and the 10m windfield size  
5. Summarize how large-scale dynamics guided Helene’s early evolution and track forcast confidence

By the end, the following will have been discussed: 
- the shear size of Helene, as it was determined to be around the 90th percentile in size for tropical cyclones that come from the Central American Gyre
- its track accuracy that was well forecasted a week in advance
- its rapid intensification and storm surge impacts along the West Coast of Florida and Apalachee Bay (explored more in the second notebook)

This notebook investigates the landfall and storm-surge impacts of Hurricane Helene (2024) along Florida’s Gulf Coast and Panhandle.  
We integrate geographic data, ERA5 fields, and surge observations to assess how Helene’s coastal impacts unfolded.

1. Review Helene’s landfall timeline and wind field structure  
2. Overlay storm surge observations with coastal topography and land use  
3. Map inundation prone regions and identify spatial vulnerability patterns  
4. Discuss Florida’s surge exposure in the context of sea level rise  
5. Conclude with implications for future hazard preparedness

# Thomas

Helene_Landfall_1: Tropycal is a very useful tool for analyzing several aspects of tropical cyclones. Some of these aspects of Helene include:
- The storm made landfall at the Big Bend region in Florida
- The maximum wind speed decreased and the pressure increased significantly after landfall
- Most tornadoes occurred on the eastern half of the system
Helene_Landfall_2: The cyclone phase space plots of Hurricane Helene can be created by utilizing TempestExtremes and CPyS, which includes inputting ERA5 and HURDAT2 data to calculate the cyclone phase space variables along Helene's track. According to the table of variables and the plots, Helene transitioned from a warm-core system to a cold-core system sometime between 0600 UTC and 1200 UTC on September 28th, 2024. This indicates when the system became post-tropical, where it proceeded to stall over the Southeastern U.S. and experience the Fujiwhara Effect with another extratropical cyclone in the region.
Future work that can be done on this notebook would be to get smoother results on the plots, as well as adding more detail to the plots, such as labeling the quadrants of what type of core the system is.

# Bianca

Hurricane Helene made landfall in September 2024, producing extreme rainfall that led to saturated soils, widespread flooding, and numerous landslides across the Appalachian Mountains (Amorim et al., 2025). The purpose of these notebooks is to visualize the landslides, streamflow discharge, and rainfall recorded at several monitoring stations throughout the mountain chain. 

This notebook utilizes data from the United States Geological Survey (USGS) water data website. Two locations across the Appalachian Mountains were selected based on the availability of data. We utilized the Matplotlib and Pandas packages for plotting and visualization, as well as handling time series and tabular datasets. The two selected locations were in Asheville and Sugar Grove, North Carolina. For this research, we plotted precipitation, discharge, and gauge height to visualize the correlation between these variables in the two locations. Then, we used data from the US Army Corps of Engineers (USACE) to visualize the streams and watersheds within the study area. According to the USACE, the combination of steep mountainous terrain and saturated soils significantly increases the likelihood of flash flooding. To visualize this dataset, we used pathlib, GeoPandas, NumPy, Matplotlib, and Cartopy to open the folder structure, read the shapefiles, and generate maps with multiple geographic features, including land, coastlines, and state boundaries. Lastly, we created an interactive map by downloading the USGS streamflow data. This interactive map shows the discharge across North Carolina during Hurricane Helene. 

Hurricane Helene was a Category 4 tropical cyclone that made landfall in September 2024. Different states across the United States suffered the impacts of this catastrophic hurricane. According to the USDA Risk Management Agency, Alabama, Florida, Georgia, Kentucky, North Carolina, Ohio, South Carolina, Tennessee, Virginia, and West Virginia were affected by Helene

# Ale

Hurricane Helene was a devastating Category 4 hurricane that made landfall in Florida's Big Bend on September 26th, 2024. Helene brought massive amounts of rainfall as it moved northward through the Tennessee Valley and the southern Appalachian Mountains (US Army Corps of Engineers - Nashville District, 2025). Storm surge, widespread flooding, extensive power outages, and wind damage were some of the many impacts caused by Hurricane Helene. Presidential disaster declarations were issued for 299 counties across 8 different states, impacting an estimated 26 million people (Sawyer, 2025).

46.5% of the counties affected by Hurricane Helene had higher-than-average social vulnerability estimates, compared to the national percentage of 30.1% of counties with higher-than-average social vulnerability estimates. Higher-than-average percentages of people living in rural areas compared to the national average were also seen in the affected counties, leading to increased difficulties for recovery efforts post-storm. Other socioeconomic vulnerabilities, such as poverty levels, also impacted the aftermath of Hurricane Helene. 