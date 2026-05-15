<img width="2500" height="978" alt="music_migration_lab_header" src="https://github.com/user-attachments/assets/6e993bbb-cc74-4081-947c-6c4de8c7f83f" />


# Mapping Jazz Diasporas

#### Team: [John Lauermann](https://www.pratt.edu/people/john-lauermann/), [Cisco Bradley](https://www.pratt.edu/people/francis-bradley/)

This document describes work supporting Dr. Cisco Bradley's _Global Jazz Diasporas_ research initiative, a collaboration with the [Music and Migration Lab](https://www.musicandmigration.com/) and the [Spatial Analysis & Visualization Initiative](https://www.pratt.edu/research/research-at-pratt/provosts-centers/spatial-analysis-visualization-initiative/) at Pratt Institute. The project documents the life travels of over 2500 musicians who played a significant role in building Jazz and Black Creative Music. The map visualizes the migration patterns from over 15500 migration movements, information based on over 500 oral histories and archival research. 


## Related products
Bradley, F. & Lauermann, J. _Global Jazz Diasporas Data Dashboard_ (last updated May 2026) https://prattsavi.maps.arcgis.com/apps/dashboards/ce4f9dbb59184ddaac73b36469c131f9


## How to replicate
The Python notebook is designed to run inside ArcGIS Pro. The source data on migration are currently embargoed pending further expansion of the migration database. Those interested in accessing the data should contact the research team to discuss potential collaborations. 
- [01_dataprep](01_dataprep.ipynb) ingests the historical database, cleans it using `pandas`, and saves to a CSV for futher use.
- [02_mapnetwork](02_mapnetwork.ipynb) geocodes the data and develops a network map of origin points, destination points, and paths between them.
- [03_webmap](03_webmap.ipynb) manages cartography programmatically for the subsequent web maps. 



