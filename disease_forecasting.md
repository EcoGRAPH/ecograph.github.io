---
layout: page
title: Disease Forecasting
subtitle: Early warning systems
bigimg: 
  - "/img/IMG_1637.JPG" : "Woreta Town Health Center, Amhara Region of Ethiopia"
---
Vector-borne disease transmission is highly variable over space and time, making it challenging to allocate resources for disease prevention, vector control and outbreak response. These patterns are often associated with variations in meteorological conditions that influence the reproduction, growth, and mortality of vector and host population along with the development and transmission of disease-causing pathogens. Monitoring environmental conditions with ground-based sensors and Earth-observing satellites can provide advance warning of disease outbreaks. However, predictive modeling of environmentally sensitive diseases is complicated by the complexities of transmission cycles and the effects of other factors related to human behavior and social environments. 

## Malaria
Malaria remains one of the most significant public health challenges in many low- and middle-income countries, particularly in sub-Saharan Africa. To make surveillance a more effective and efficient core intervention, there is a need to shift from a reactive to a predictive approach by using models to forecast malaria risk. Our work on malaria early warning systems has involved developing and testing predictive models of weekly malaria cases in the epidemic-prone Amhara region of Ethiopia (Midekisa et al. 2012, Davis et al. 2019, Nekorchuk et al. 2021). We have also evaluated the accuracy of different sources of geospatial environmental data (Alemu and Wimberly 2020) and developed informatics tools to facilitate access to satellite Earth observations for malaria early warning (Liu et al. 2015; Wimberly et al. 2022). In collaboration with partners in the Ethiopian public health sector, we created the Epidemic Prognosis Incorporating Disease and Environmental Modeling for Integrated Assessment (EPIDEMIA) system for implementing malaria forecasting (Merkord et al. 2017) and conducted a scoping study to develop a roadmap for scaling malaria early warning systems to a national level in Ethiopia (Wimberly and Nekorchuk 2021). EPIDEMIA is implemented in the free and open-source R software for statistical computing and the code is freely available on GitHub.

### References
* Wimberly, M. C., D. M. Nekorchuk, and R. R. Kankanala. 2022. [Cloud-based applications for accessing satellite Earth observations to support malaria early warning](https://www.nature.com/articles/s41597-022-01337-y). Scientific Data 9: 208. 
*  McMahon, A., A. Mihretie, A. A. Ahmed, M. Lake, W. Awoke, and M. C. Wimberly. 2021. [Remote sensing of environmental risk factors for malaria in different geographic contexts](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-021-00282-0). International Journal of Health Geographics 20: 28.
* Nekorchuk, D. M., T. Gebrehiwot, M. Lake, W. Awoke, A. Mihretie, and M. C. Wimberly. 2021. [Comparing malaria early detection methods in a declining transmission setting in northwestern Ethiopia](https://bmcpublichealth.biomedcentral.com/articles/10.1186/s12889-021-10850-5). BMC Public Health 21: 788.
* Wimberly, M. C., and D. M. Nekorchuk. 2021. [Malaria Early Warning in Ethiopia: A Roadmap for Scaling to the National Level](https://www.climatelinks.org/resources/malaria-early-warning-ethiopia-roadmap-scaling-national-level). U.S. Agency for International Development. 
* Alemu, W. G., and M. C. Wimberly. 2020. [Evaluation of remotely sensed and interpolated environmental datasets for vector-borne disease monitoring using *in situ* observations over the Amhara Region, Ethiopia](https://www.mdpi.com/1424-8220/20/5/1316/htm). Sensors 20: 1316.
* Davis, J. K., Gebrehiwot, T., Worku. M., Awoke, W., Mihretie, A., Nekorchuk, D., and M. C. Wimberly. 2019. [A genetic algorithm for identifying spatially-varying environmental drivers in a malaria time series model](https://www.sciencedirect.com/science/article/pii/S136481521930129X). Environmental Modelling and Software 119: 275-284.
* Merkord, C. L., Y. Liu, A. Mihretie, T. Gebrehiwot, W. Awoke, E. Bayabil, G. M. Henebry, G. T. Kassa, M. Lake, and M. C. Wimberly. 2017. [Integrating malaria surveillance with climate data for outbreak detection and forecasting: the EPIDEMIA system](https://malariajournal.biomedcentral.com/articles/10.1186/s12936-017-1735-x). Malaria Journal 16:89.
* Liu, Y., J. Hu, I. Snell-Feikema, M. S. VanBemmel, A. Lamsal, M. C. Wimberly. 2015. [Software to facilitate remote sensing data access for disease early warning systems](https://www.sciencedirect.com/science/article/pii/S1364815215300116). Environmental Modelling and Software 74: 238-246. 
* Midekisa, A., G. Senay, G. M. Henebry, P. Semuniguse, and M. C. Wimberly. 2012. [Remote sensing-based time series models for malaria early warning in the highlands of Ethiopia](https://malariajournal.biomedcentral.com/articles/10.1186/1475-2875-11-165). Malaria Journal 11: 165.

## West Nile virus
West Nile virus is the most common mosquito-borne disease in the United States, causing more than 53,000 reported disease cases and 2,500 deaths since it was introduced in 1999. The Northern Great Plains have consistently been a hot spot of WNV incidence, with most cases concentrated in a few specific locations and occurring in a small number of outbreak years (Wimberly et al. 2013). Because of the relatively short disease transmission season, weather conditions in the spring and early summer influence the rate of virus amplification in mosquitoes and avian hosts and the subsequent risk of spillover into human populations (Wimberly et al. 2014). We developed a regional forecasting model that predicted WNV cases as a function of the rates of vegetation greenup and degree day accumulation during spring and summer (Chuang and Wimberly, 2012). This model was later refined to increase accuracy by incorporating both meteorological variables and mosquito infection rates as predictors (Davis et al. 2017, 2018). The approach was implemented as the Arbovirus Monitoring and Prediction (ArboMAP) system, which has been used to forecast WNV in South Dakota beginning in 2016. A retrospective validation of ArboMAP forecasts in South Dakota found that integrating environmental data with mosquito surveillance data increased the accuracy of WNV forecasts, and that accurate forecasts would be made early enough in the season to inform disease prevention and mosquito control activities prior to the peak of human transmission (Wimberly et al. 2022).

### References
* Wimberly, M. C., J. K. Davis, M. B. Hildreth, and J. Clayton. 2022. [Integrated forecasts based on public health surveillance and meteorological information predict West Nile virus in a high-risk region of North America](https://ehp.niehs.nih.gov/doi/10.1289/EHP10287). Environmental Health Perspectives 130(8): 087006.
* Davis, J. K., G. P. Vincent, M. B. Hildreth, L. Kightlinger, C. Carlson, and M. C. Wimberly. 2018. [Improving the prediction of arbovirus outbreaks: a comparison of climate-driven models for West Nile virus in an endemic region of the United States](https://www.sciencedirect.com/science/article/pii/S0001706X18300512). Acta Tropica 185: 242-250.
* Davis, J. K., G. P. Vincent, M. B. Hildreth, L. Kightlinger, C. Carlson, and M. C. Wimberly. 2017. [Integrating environmental monitoring and mosquito surveillance to predict vector-borne disease: Prospective forecasts of a West Nile virus outbreak](http://currents.plos.org/outbreaks/index.html%3Fp=73093.html). PLoS Currents Outbreaks. 2017 May 23. Edition 1. doi: 10.1371/currents.outbreaks.90e80717c4e67e1a830f17feeaaf85de.
* Wimberly, M. C., A. Lamsal, P. Giacomo, and T. Chuang. 2014. [Regional variation of climatic influences on West Nile virus outbreaks in the United States](http://www.ajtmh.org/content/journals/10.4269/ajtmh.14-0239). American Journal of Tropical Medicine and Hygiene 91: 677-684. 
* Wimberly, M. C., P. Giacomo, L. Kightlinger, and M. B. Hildreth. 2013. [Spatio-temporal epidemiology of human West Nile virus disease in South Dakota](https://www.mdpi.com/1660-4601/10/11/5584). International Journal of Environmental Research and Public Health 10: 5584-5602.
* Chuang T., and M. C. Wimberly. 2012. [Remote Sensing of Climatic Anomalies and West Nile Virus Incidence in the Northern Great Plains of the United States](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0046882). PLoS One 7:e46882.