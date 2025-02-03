# General Transit Feed Specification (GTFS) 

## Introduction

The **General Transit Feed Specification (GTFS)** is a standard format for public transportation schedules and associated geographic information. It enables transit agencies to publish their data in a format that can be easily consumed by a wide range of applications and researchers. GTFS data includes details about routes, stops, trips, and schedules, making it invaluable for analysing and optimising public transport systems.

The importance of GTFS lies in its role in enhancing data-driven decision-making for urban mobility. It facilitates the integration of public transit data into navigation apps, transit planning tools, and research models, thereby improving the efficiency and accessibility of public transport systems worldwide.

GTFS plays a pivotal role in human mobility, traffic, and transport research. It provides a foundation for innovative approaches to public transport emission analysis, enabling researchers and policymakers to assess environmental impacts more accurately. This repository presents initial analyses and data visualisations using GTFS data to demonstrate its application in real-world scenarios.

## Useful Sources for GTFS

- **R Packages:**
  - `gtfstools`
  - `tidytransit`
  - `gtfs2emis`
  - `gtfsrouter`

- **Python Libraries:**
  - `GTFS KIT`
  - `pygtfs`

- **Esri Tools:**
  - [Public Transit Tools](https://github.com/Esri/public-transit-tools)

- **Other Tutorials and Resources:**
  - [GTFS Specification](https://developers.google.com/transit/gtfs/reference)
  - [GTFS Headways](https://perkinsandwill.github.io/nn_r_training/posts/gtfs-data/)
  - [GTFS Segments](https://github.com/UTEL-UIUC/gtfs_segments)
  - [Definitive Guide to GTFS](https://stuebinm.eu/bookshelf/gtfs/ch-00-definitive-guide-to-gtfs.html)
  - [Transit Operations and Capacity](https://eng.libretexts.org/Bookshelves/Civil_Engineering/Fundamentals_of_Transportation/04%3A_Transit/4.02%3A_Transit_Operations_and_Capacity)

## GTFS in Developing Countries: A Case Study of Vietnam

This repository includes a case study focusing on Vietnam, specifically Hanoi and Ho Chi Minh City (HCMC). Both cities are undergoing significant transformations in their public transit systems. Hanoi and HCMC feature extensive bus networks, and both Hanoi and HCMC has recently introduced a new metro system to enhance urban mobility.

Initial analysis of bus transit in HCMC has been conducted and is available in the `vinif_bus_time_tables` repo. Further analyses using these data sources will be updated regularly.

### Data Sources for the Vietnam Case Study:
- [GTFS Data for Hanoi - TUMI Data Hub](https://hub.tumidata.org/dataset/gtfs-hanoi/resource/4b9a9939-ff2a-4fe9-985f-63b927b39655)
- [GTFS Data for Hanoi - World Bank](https://datacatalog.worldbank.org/search/dataset/0038236/Hanoi--Vietnam---General-Transit-Feed-Specification--GTFS-)
- [Vietnam Bus Maps Feed List](https://busmaps.com/en/vietnam/feedlist)
