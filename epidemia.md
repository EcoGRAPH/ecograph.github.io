---
layout: page
title: EPIDEMIA
subtitle: Malaria early warning in Ethiopia
bigimg: 
  - "/img/IMG_1637.JPG" : "Woreta Town Health Center, Amhara Region of Ethiopia"
---

## Project Description

Outbreaks of malaria are often linked to climate variations and land use changes that affect the life cycles of the mosquito vector and the Plasmodium parasite. Early warning of the timing and locations of these epidemics can facilitate more effective targeting of resources for disease prevention, control, and treatment. We have developed the Epidemic Prognosis Incorporating Disease and Environmental Monitoring for Integrated Assessment (EPIDEMIA) system to support malaria forecasting in epidemic-prone regions of Ethiopia. EPIDEMIA uses machine-learning methods with malaria surveillance data and environmental data from Earth-observing satellites to determine the relationships between climate variations and malaria outbreaks. The system provides an open-source software toolbox for data harmonization, predictive analytics, and report generation implemented in the R language and software environment. Remotely sensed data are accessed through a Google Earth Engine application that supports cloud-based data processing and produces downloadable summaries for use with EPIDEMIA. The software is usable with existing public health surveillance databases and can be run on a variety of computer systems. 

![EPIDEMIA environmental data](/img/Ethiopia_RS_25SEP2020.JPG)<br/>
*Examples of remotely-sensed environment data used in EPIDEMIA, including MODIS land surface temperature (left), and rainfall data from the Global Precipitation Mission (Right).*

The first step in implementing EPIDEMIA is to acquire historical epidemiological and environmental data for the region of interest and develop a harmonized dataset for modeling. These data are then used to identify geographic strata for modeling and calibrate the predictive models. To generate weekly forecasts, the system is updated with recent data, model predictions are generated for the upcoming twelve weeks, and the results are used to generate a formatted report with maps and charts. Forecasting is fully automated, and the necessary data processing, modeling, and report generation steps are carried out by running a single script. A separate validation module can be used to generate retrospective forecasts and evaluate their predictive skill using historical data.

![EPIDEMIA forecast graph](/img/EPIDEMIA_diagram_25SEP2020.JPG)<br/>
*Flowchart of the EPIDEMIA system illustrating the steps for generating a weekly forecast.*

EPIDEMIA is developed by an interdisciplinary team that includes scientists from the University of Oklahoma along with collaborators from Ethiopian public health agencies, non-governmental organizations, and universities. The system has been piloted and tested through a demonstration project in the Amhara region of Ethiopia. We are now working with United State Agency for International Development and the U.S. President’s Malaria Initiative to develop a roadmap for scaling up malaria early warning with EPIDEMIA to a national level. This work involves evaluating national-level malaria surveillance datasets, using these data to assess malaria environment relationships, upgrading the EPIDEMIA software system, and engaging with a variety of stakeholders in Ethiopia. This page provides links to project outputs including software code, documentation, and data. More details about the underlying research are provided on our [malaria epidemiology page](http://ecograph.net/malaria/). For more information about EPIDEMIA contact Dr. Michael Wimberly, the principal investigator.

## Software and Data

### epidemiar-demo - Example implementation of EPIDEMIA for malaria forecasting in Ethiopia
* [epidemiar-demo GitHub archive](https://github.com/EcoGRAPH/epidemiar-demo)
* [Detailed Walk-through Guide](https://github.com/EcoGRAPH/epidemiar-demo/blob/master/documentation/epidemiar-demo_EPIDEMIA_walkthrough.pdf)
* [Installation Guide](https://github.com/EcoGRAPH/epidemiar-demo/blob/master/documentation/epidemiar-demo_installation_guide.pdf)
* [Validation Guide](https://github.com/EcoGRAPH/epidemiar-demo/blob/master/documentation/epidemiar-demo_validation_guide.pdf)

### R package for disease modeling, forecasting, and early detection
* [epidemiar GitHub archive](https://github.com/EcoGRAPH/epidemiar): functions for malaria modeling, forecasting, validation, and early detection & early warning alerts.
* [clusterapply GitHub archive](https://github.com/EcoGRAPH/clusterapply): functions for implementing malaria forecasting models across multiple geographic strata.

### Google Earth Engine (GEE) applications for accessing remotely-sensed data
* [GEE app for downloading and visualizing woreda-level data](https://dawneko.users.earthengine.app/view/epidemiar-ethiopia-demo). 
* [GEE scripts for downloading and visualizing woreda-level data summaries](https://code.earthengine.google.com/d53a6c47f3fe638d469955404273c568). Requires a GEE account to run.
* [GEE App and Script Walk-Through Guide](https://github.com/EcoGRAPH/ecograph.github.io/blob/master/docs/GEE_app_ce_walkthrough_20200901.pdf)

## Partner Organizations
* [Amhara Public Health Institute](https://www.facebook.com/HealthofInstitute/)
* [Bahir Dar University](http://www.bdu.edu.et/)
* [Ethiopian Public Health Institute](https://www.ephi.gov.et/)
* [Health, Development, and Anti-Malaria Association](http://www.hdama.org/)

## Funding Sources
* NASA (NNX11AF67G
* NIAID (R01AI079411)
* USAID (AID-OAA-TO-14-00044 SUB-778)

## Publications
* Davis, J. K., Gebrehiwot, T., Worku. M., Awoke, W., Mihretie, A., Nekorchuk, D., and M. C. Wimberly. 2019. [A genetic algorithm for identifying spatially-varying environmental drivers in a malaria time series model](https://www.sciencedirect.com/science/article/pii/S136481521930129X?via%3Dihub). Environmental Modelling and Software 119: 275-284.
* Merkord, C. L., Y. Liu, A. Mihretie, T. Gebrehiwot, W. Awoke, E. Bayabil, G. M. Henebry, G. T. Kassa, M. Lake, and M. C. Wimberly. 2017. [Integrating malaria surveillance with climate data for outbreak detection and forecasting: the EPIDEMIA system](https://malariajournal.biomedcentral.com/articles/10.1186/s12936-017-1735-x). Malaria Journal 16:89.
* Liu, Y., J. Hu, I. Snell-Feikema, M. S. VanBemmel, A. Lamsal, M. C. Wimberly. 2015. [Software to facilitate remote sensing data access for disease early warning systems](https://www.sciencedirect.com/science/article/pii/S1364815215300116). Environmental Modelling and Software 74: 238-246. 
* Midekisa A., B. Beyene, A. Mihretie, E. Bayabil, M. C. Wimberly. 2015. [Seasonal associations of climatic drivers and malaria in the highlands of Ethiopia](https://parasitesandvectors.biomedcentral.com/articles/10.1186/s13071-015-0954-7). Parasites & Vectors 8: 339. 
* Midekisa, A., G. Senay, G. M. Henebry, P. Semuniguse, and M. C. Wimberly. 2012. [Remote sensing-based time series models for malaria early warning in the highlands of Ethiopia](https://malariajournal.biomedcentral.com/articles/10.1186/1475-2875-11-165). Malaria Journal 11: 165.
