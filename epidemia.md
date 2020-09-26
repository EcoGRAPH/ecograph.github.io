---
layout: page
title: EPIDEMIA
subtitle: Malaria early warning in Ethiopia
bigimg: 
  - "/img/IMG_1637.JPG" : "Woreta Town Health Center, Amhara Region of Ethiopia"
---

## Project Description

Outbreaks of malaria are often linked to climate variations and land use changes that affect the life cycles of the mosquito vector and the Plasmodium parasite. Early warning of the timing and locations of these epidemics can facilitate more effective targeting of resources for disease prevention, control, and treatment. We have developed the Epidemic Prognosis Incorporating Disease and Environmental Monitoring for Integrated Assessment (EPIDEMIA) system to support malaria forecasting in epidemic-prone regions of Ethiopia. EPIDEMIA uses machine-learning methods with malaria surveillance data and environmental data from Earth-observing satellites to determine the relationships between climate variations and malaria outbreaks. The system provides an open-source software toolbox for data harmonization, predictive analytics, and report generation implemented in the R language and software environment. Remotely sensed data are accessed through a Google Earth Engine application that supports cloud-based data processing and produces downloadable summaries for use with EPIDEMIA. The software is usable with existing public health surveillance databases and can be run on a variety of computer systems. 

![EPIDEMIA environmental data](/img/EPIDEMIA_diagram_22MAR2019.png)<br/>
*Examples of remotely-sensed environment data used in EPIDEMIA, including MODIS land surface temperature (left), and rainfall data from the Global Precipitation Mission (GPM).*

The first step in implementing EPIDEMIA is to acquire historical epidemiological and environmental data for the region of interest and develop a harmonized dataset for modeling. These data are then used to identify geographic strata for modeling and calibrate the predictive models. To generate weekly forecasts, the system is updated with recent data, model predictions are generated for the upcoming twelve weeks, and the results are used to generate a formatted report with maps and charts. Forecasting is fully automated, and the necessary data processing, modeling, and report generation steps are carried out by running a single script. A separate validation module can be used to generate retrospective forecasts and evaluate their predictive skill using historical data.

![EPIDEMIA forecast graph](/img/EPIDEMIA_forecasts_22MAR2019.png)<br/>
*Flowchart of the EPIDEMIA system illustrating the steps for generating a weekly forecast.*

EPIDEMIA is developed by an interdisciplinary team that includes scientists from the University of Oklahoma along with collaborators from Ethiopian public health agencies, non-governmental organizations, and universities. The system has been piloted and tested through a demonstration project in the Amhara region of Ethiopia. We are now working with United State Agency for International Development and the U.S. President’s Malaria Initiative to develop a roadmap for scaling up malaria early warning with EPIDEMIA to a national level. This work involves evaluating national-level malaria surveillance datasets, using these data to assess malaria environment relationships, upgrading the EPIDEMIA software system, and engaging with a variety of stakeholders in Ethiopia. This page provides links to project outputs including software code, documentation, and data. More details about the underlying research are provided on our malaria epidemiology page. For more information about EPIDEMIA contact Dr. Michael Wimberly, the principal investigator.

## Software and Data

### epidemiar - R package for disease modeling, forecasting, and early detection
* [epidemiar GitHub archive](https://github.com/EcoGRAPH/epidemiar)


### epidemiar-demo - Example implementation of epidemiar for malaria forecasting in Ethiopia
* [epidemiar-demo GitHub archive](https://github.com/EcoGRAPH/epidemiar-demo)

## Partner Organizations

* [South Dakota State University](https://www.sdstate.edu/)
* [Amhara Regional Health Bureau](http://www.moh.gov.et/da/web/guest/amhara-regional-health-bureau)
* [Health, Development, and Anti-Malaria Association](http://www.hdama.org/)
* [Bahir Dar University](http://www.bdu.edu.et/)

## Publications

* Davis, J. K., Gebrehiwot, T., Worku. M., Awoke, W., Mihretie, A., Nekorchuk, D., and M. C. Wimberly. 2019. [A genetic algorithm for identifying spatially-varying environmental drivers in a malaria time series model](https://www.sciencedirect.com/science/article/pii/S136481521930129X?via%3Dihub). Environmental Modelling and Software 119: 275-284.
* Merkord, C. L., Y. Liu, A. Mihretie, T. Gebrehiwot, W. Awoke, E. Bayabil, G. M. Henebry, G. T. Kassa, M. Lake, and M. C. Wimberly. 2017. [Integrating malaria surveillance with climate data for outbreak detection and forecasting: the EPIDEMIA system](https://malariajournal.biomedcentral.com/articles/10.1186/s12936-017-1735-x). Malaria Journal 16:89.
* Alemu, H. T., A. T. Kaptue, B. G. Senay, M. C. Wimberly, and G. M. Henebry. 2015. [Evapotranspiration in the Nile Basin: Identifying dynamics and drivers, (2002-2011)](https://www.mdpi.com/2073-4441/7/9/4914). Water 7: 4914-4931.
* Liu, Y., J. Hu, I. Snell-Feikema, M. S. VanBemmel, A. Lamsal, M. C. Wimberly. 2015. [Software to facilitate remote sensing data access for disease early warning systems](https://www.sciencedirect.com/science/article/pii/S1364815215300116). Environmental Modelling and Software 74: 238-246. 
* Midekisa A., B. Beyene, A. Mihretie, E. Bayabil, M. C. Wimberly. 2015. Seasonal associations of climatic drivers and malaria in the highlands of Ethiopia. Parasites & Vectors 8: 339. 
* Midekisa A., B. Beyene, A. Mihretie, E. Bayabil, M. C. Wimberly. 2015. [Seasonal associations of climatic drivers and malaria in the highlands of Ethiopia](https://parasitesandvectors.biomedcentral.com/articles/10.1186/s13071-015-0954-7). Parasites & Vectors 8: 339. 
* Wimberly, M. C., and A. Midekisa. 2014. [Hydro-epidemiology of the Nile Basin: Understanding the complex linkages between water and infectious diseases](https://www.researchgate.net/publication/262912212_Hydro-Epidemiology_of_the_Nile_Basin_Understanding_the_Complex_Linkages_Between_Water_and_Infectious_Diseases). Pages 219-236 In: A. M. Melesse, W. Abtew, and S. G. Setegn, editors. Nile River Basin: Ecohydrological Challenges, Climate Change and Hydropolitics. Springer, New York.
* Midekisa, A., G. Senay, G. M. Henebry, P. Semuniguse, and M. C. Wimberly. 2012. [Remote sensing-based time series models for malaria early warning in the highlands of Ethiopia](https://malariajournal.biomedcentral.com/articles/10.1186/1475-2875-11-165). Malaria Journal 11: 165.
* Wimberly, M. C., A. Midekisa, P. Semuniguse, H. Teka, G. M. Henebry, T. Chuang, and G. B. Senay. 2012. [Spatial synchrony of malaria outbreaks in a highland region of Ethiopia](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1365-3156.2012.03058.x). Tropical Medicine & International Health 17: 1192-1201.
