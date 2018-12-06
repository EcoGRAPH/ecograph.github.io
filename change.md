---
layout: page
title: CHANGE
subtitle: Coupled Human and Natural Geospatial Environments
bigimg: 
  - "/img/Colorado_WUI.JPG" : "Wildland-urban interface in the Colorado Front Range"
---

## Project Description

Climate change is having myriad effects on ecosystems worldwide, with natural and human-caused disturbances serving as major drivers. In addition, increasing human exploitation of fire-prone ecosytems is altering fire regimes, increase human vulnerability, and limiting management options. To better understand the implications of these changes, there is a need for simulation models that can project future landscape dynamics in the context of changing climates and expanding human populations. We developed an integrated land change simulator by coupling a model of natural disturbances and vegetation dynamics (LADS, the LAndscape Dynamics Simulator developed by Mike Wimberly) with a model of human driven land use and land cover change (FORE-SCE, the FOREcasting SCEnarios of future land cover model developed by Terry Sohl at the USGS Center for Earth Resources Observation and Science). The result is a novel model for Simulating Coupled Human and Natural Environments (CHANGE). 

![CHANGE system flowchart](/img/CHANGE_flowchart.jpg)<br/>
*Conceptual diagram of the CHANGE simulation model.*

The CHANGE model simulates gridded landscapes classified into discrete land use and land cover (LULC) classes such as developed land, forest, shrubland, and cropland. Transitions between these LULC classes are modeled using a demand-allocation algorithm that was adapted from FOR-SCE. Naturally-vegetated LCLU classes are further divided into vegetation states that represent unique combinations of vegetation structure and species composition . Within these naturally-vegetated areas, succession is modeled deterministically using a state-and-transition model, and wildfires are modeled using a stochastic cellular fire spread algorithm derived from LADS. CHANGE also includes new components for explicitly modeling the human-natural interface (HNI) as a hybrid LULC class. Examples of the HNI include low-density housing in fire-prone forests in the western United States and small-scale agricultural encroachment into tropical forests in West Africa.

![CHANGE sample output](/img/Change_example.jpg)<br/>
*Output of the CHANGE model with examples of landscape change in the Colorado Front Range: A) Wildland-urban interface expansion, B) Wildfire in the Wildland-urban interface, C) Urban growth, and D) Wildfire outside of the wildland-urban interface.*

## Partner Organizations

* [USGS Center for Earth Resources Observation and Science](https://eros.usgs.gov/)
* [SERVIR West Africa](https://servirglobal.net/Regions/West-Africa)

## Publications

* Sohl, T. L., M. C. Wimberly, V. C. Radeloff, D. M. Theobald, B. M. Sleeter. 2016. [Divergent projections of future land use in the United States arising from different models and scenarios](https://www.sciencedirect.com/science/article/pii/S0304380016302605?via%3Dihub). Ecological Modelling 337: 281–297
* Liu, Z., M. C. Wimberly, A. Lamsal, T. L. Sohl, T. J. Hawbaker. 2015. [Climate change and wildfire risk in an expanding wildland-urban interface: a case study from the Colorado Front Range Corridor](https://link.springer.com/article/10.1007%2Fs10980-015-0222-4). Landscape Ecology 30: 1943-1957.
* Wimberly, M. C. T. L. Sohl, Z. Liu, and A. Lamsal. 2015. [Simulating forest landscapes as coupled human and natural systems](https://www.researchgate.net/publication/283779881_Simulating_Forest_Landscape_Disturbances_as_Coupled_Human_and_Natural_Systems). Pages 233-216 In: A. Perera, B. Sturtevant, and L. Buse, editors. Modeling Forest Landscape Disturbances. Springer, New York.
* Kennedy, R. S. H., and M. C. Wimberly. 2009. [Historical fire and vegetation dynamics in dry forests of the interior Pacific Northwest, USA and relationships to Northern Spotted Owl (Strix occidentalis caurina) habitat conservation](https://www.sciencedirect.com/science/article/pii/S0378112709002977). Forest Ecology and Management 258: 554-566.
* Wimberly, M. C., and R. S. H. Kennedy. 2008. [Spatially explicit modeling of mixed-severity fire regimes and landscape dynamics in the interior Pacific Northwest](https://www.sciencedirect.com/science/article/pii/S0378112707005051). Forest Ecology and Management 254: 511-523.
* Nonaka, E., T. A. Spies, M. C. Wimberly, and J. L. Ohmann. 2007. [Historical range of variability (HRV) in live and dead wood biomass: a regional-scale simulation study](http://www.nrcresearchpress.com/doi/abs/10.1139/X07-064#.XAQexC2ZNBw). Canadian Journal of Forest Research 37: 2349-2364. 
* Wimberly, M. C. 2002. [Spatial simulation of historical landscape patterns in coastal forests of the Pacific Northwest](http://www.nrcresearchpress.com/doi/abs/10.1139/x02-054#.XAQmBS2ZNBw). Canadian Journal of Forest Research 32: 1316-1328.
* Wimberly, M. C., T. A. Spies, C. J. Long, and C. Whitlock. 2000. [Simulating Historical Variability in the Amount of Old Forests in the Oregon Coast Range](https://onlinelibrary.wiley.com/doi/full/10.1046/j.1523-1739.2000.98284.x). Conservation Biology 14: 167-180.
