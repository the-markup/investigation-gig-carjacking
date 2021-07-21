# Gig Worker Carjackings

This repository contains data from our story, "[TK]()."


## Data

`data/carjackings.csv` catalogs instances of gig workers being carjacked on the job, sourced using news and police reports.

Data in the file is arranged as follows:

| Column	| Description |
|---------|-------------|
| **`state`**	| State where incident took place.
| **`city`** |	City where incident took place. If the city is in a larger metropolitan area, that is indicated in parentheses.
| **`date`** |	Date incident took place.
| **`company`** |	App that gig worker was using at time of incident.
| **`carjacking_happened_via_the_app`** |	Whether the alleged assailant(s) hailed the driver through the app or if the incident happened randomly on the street, based on descriptions found in the sources. Marked "Yes," "No," or "Unclear."
| **`driver_deceased`** |	Whether the driver was killed as a result of the incident.
| **`source`** |	Where information was gathered to confirm incident.
| **`additional_sources`** |	Additional confirmation of the incident.
