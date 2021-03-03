---
layout: page
title: ArboMAP
subtitle: Arbovirus Mapping and Prediction to Forecast Mosuqito-Borne Disease Outbreaks
bigimg: 
  - "/img/Culex_mosquito.jpg" : "Engorged culicine mosquito (CDC PHIL)"
---

## Project Description

West Nile virus (WNV) is endemic in the United States and poses a persistent threat to public health. In particular, the Northern Great Plains are a hot spot for WNV transmission, and South Dakota has the highest long-term incidence of West Nile neuroinvasive disease in the country. We have conducted research on WNV epidemiology to explore the environmental risk factors that affect transmission to humans. The spatial and temporal distributions of vector mosquitoes and bird hosts, and the risk of disease in humans are strongly influenced by temperature, humidity, vegetation, soils, and land use. These relationships can be quantified using mathematical models and applied to develop maps of WNV risk and forecast the probability of future outbreaks. 

![ArboMAP system flowchart](/img/Arbomap_system.jpg)<br/>
*Conceptual diagram of information flow through the ArboMAP system.*

We have applied these results to develop a WNV early warning system for South Dakota that combines environmental monitoring with mosquito surveillance produce weekly maps of WNV risk during the transmission season. The Arbovirus Mapping and Prediction (ArboMAP) system ingests gridded meteorological data using Google Earth Engine, a cloud-based platform for Earth science data analysis. Mosquito abundance and testing data are uploaded from locations throughout the state via a web-based surveillance platform. Statistical models are used to estimate the mosquito infection rate from recent surveillance data, and to predict numbers of human cases based on mosquito infection rate, temperature, and humidity. These models are implemented using the R programming landuage and sofware environment, and all code is publically available via GitHub. This work is supported in part by a grant from the NASA Applied Sciences Public Health and Air Quality Program (NNX15AF74G).

![ArboMAP predictions](/img/WNV_predictions.jpg)<br/>
*Prospective WNV forecasts. Black line/Gray shading: prediction with 95% intervals; Red line: Observed cases in 2016 or 2017; Dashed line: Observed cases in 2012; Dotted line: Observed cases in 2015.*

## Software and Data

[ArboMAP Software Archive](https://github.com/EcoGRAPH/ArboMAP)

## Partner Organizations

* Louisiana Department of Health
* OKC County Health Department
* Oklahoma State Department of Health 
* Michigan Department of Health and Human Services
* South Dakota Department of Health
* South Dakota State University

## Publications

* Vincent, G. P., J. K. Davis, M. C. Wimberly, C. D. Carlson, and M. B. Hildreth. 2018. Permethrin susceptibility for the vector Culex tarsalis and a nuisance mosquito Aedes vexans in an area endemic for West Nile virus. BioMed Research International, Article ID 2014746.
* Davis, J. K., G. P. Vincent, M. B. Hildreth, L. Kightlinger, and M. C. Wimberly. 2018. Improving the prediction of arbovirus outbreaks: a comparison of climate-driven models for West Nile virus in an endemic region of the United States. Acta Tropica 185: 242-250.
* Davis J. K., Vincent G. P., Hildreth M. B., Kightlinger L., Carlson C., and M. C. Wimberly. 2017. Integrating Environmental Monitoring and Mosquito Surveillance to Predict Vector-borne Disease: Prospective Forecasts of a West Nile Virus Outbreak. PLoS Currents Outbreaks. 2017 May 23. Edition 1. doi: 10.1371/currents.outbreaks.90e80717c4e67e1a830f17feeaaf85de.
* Wimberly, M. C., A. Lamsal, P. Giacomo, and T. Chuang. 2014. Regional variation of climatic influences on West Nile virus outbreaks in the United States. American Journal of Tropical Medicine and Hygiene 91: 677-684. 
* Wimberly, M. C., P. Giacomo, L. Kightlinger, and M. B. Hildreth. 2013. Spatio-temporal epidemiology of human West Nile virus disease in South Dakota. International Journal of Environmental Research and Public Health 10: 5584-5602.
* Chuang, T., C. W. Hockett, L. Kightlinger, and M. C. Wimberly. 2012. Landscape-level spatial patterns of West Nile virus risk in the northern Great Plains. American Journal of Tropical Medicine and Hygiene 86: 724-731.
* Chuang, T., G. M Henebry, J. S. Kimball, D.L. VanRoekel-Patton, M. B. Hildreth, and M. C. Wimberly. 2012. Satellite microwave remote sensing for environment modeling of mosquito population dynamics. Remote Sensing of Environment 125: 147-156. 
* Chuang T., and M. C. Wimberly. 2012. Remote Sensing of Climatic Anomalies and West Nile Virus Incidence in the Northern Great Plains of the United States. PLoS One 7:e46882.
* Chuang, T. M. B. Hildreth, M. B., D. L. VanRoekel, and M. C. Wimberly. 2011. Weather and land cover influences on mosquito populations in Sioux Falls, South Dakota. Journal of Medical Entomology 48: 669-679. 
* Wey, C. L., J. Griesse, L. Kightlinger, and M. C. Wimberly. 2009. Geographic variability in geocoding success for West Nile virus cases in South Dakota, USA. Health & Place 15: 1108-1114.
* Wimberly, M. C., M. B. Hildreth, S. P. Boyte, E. Lindquist, and L. Kightlinger. 2008. Ecological niche of the 2003 West Nile virus epidemic in the northern Great Plains of the United States. PLoS One 3: e3744.
