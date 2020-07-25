---
layout: page
title: WAForDD
subtitle: West Africa Forest Degradation Data System
bigimg: 
  - "/img/Degraded_Ghana_2013.JPG" : "Degraded Forest, Brong Ahafo Region of Ghana"
---

## Project Description

The West Africa Forest Degradation Data system (WAForDD) was developed to provide annual estimates of canopy cover change in the forest reserves of Ghana. The system uses a historical Landsat imagery to generate a time series of canopy cover from 2001-present along with disturbance and recovery rates from 2003-present. Canopy cover is estimated using a random forests machine learning algorithm and extensive training and validation datasets derived from very-high resolution satellite imagery. The LandTrendr temporal segmentation is then applied to the canopy cover time series for each pixel to distinguish forest disturbance and recovery from periods of relative stability. We found that thsi approach can detect forest degradation that results in partial canopy removal as well as complete forest loss and post-disturbance recovery. Canopy cover remained relatively stable in protected areas such as National Parks, but was reduced by forest degradation and loss from logging, fire, illegal mining, and agricultural encroachment in many of the other forest reserves. 

![UG Forest Photo](/img/Bobiri_forest_v2.jpg)<br/>
*Closed canopy forest in the Bobiri Reserve, Ghana.*

WAForDD was impelemented using Google Earth Engine (GEE), a cloud-based platform for geospatial analysis that provides access to the Landsat archive as well as many other Earth observation datasets. A major goal of the WAForDD project was to develop a system that could be transferred to partner organizations in Ghana for sustainable implementation. GEE enables this objective by providing access to data and code through via a web-based intergrated development environment eliminating the need to download, store, and process large volumes of remote sensing imagery. We also developed a stand-along web application to facilitate data visualization and summarization. GEE programmers can explore the  code archive and read the project documentation for more detailed information. Those wishing to explore the annual change data in more detail should use the WAForDD GEE App.

![WAForDD Map](/img/tano_offin_timeseries_v2.jpg)<br/>
*Forest change maps from the West Africa Forest Degradation Data system (WAForDD) Version 2.1. The maps show the Desiri, Tano Offin, and Tano Offin Extension reserves.*

## Partner Organizations

* [Centre for Remote Sensing and Geographic Information Services](http://www.cersgis.org/)
* [Forestry Commission of Ghana](http://www.fcghana.org/)
* [SERVIR West Africa](https://servirglobal.net/Regions/West-Africa)

## Data and Software

* [WAForDD GEE App - Visualize forest change data and download summaries](https://mcwimberly.users.earthengine.app/view/wafordd21)
* [WaForDD GEE Code Archive (GEE account required)](https://code.earthengine.google.com/?accept_repo=users/servir_wa/WAforDD)
* [WAForDD User Guide](/docs/WAFORDD_User_Guide_28FEB2020.pdf)
