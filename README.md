# Gig Worker Carjackings

This repository contains data from our stories, "[More Than 350 Gig Workers Carjacked, 28 Killed, Over the Last Five Years](https://themarkup.org/working-for-an-algorithm/2022/07/28/more-than-350-gig-workers-carjacked-28-killed-over-the-last-five-years)" and "[Uber And Lyft Drivers Are Being Carjacked at Alarming Rates](https://themarkup.org/working-for-an-algorithm/2021/07/22/uber-and-lyft-drivers-are-being-carjacked-at-alarming-rates)." 

This repository was originally published on July 22, 2021, and later updated on July 28, 2022.

## Data

`data/carjackings.csv` catalogs instances of gig workers being carjacked on the job, sourced using news and police reports.

Data in the file is arranged as follows:

| Column	| Description |
|---------|-------------|
| **`state`**	| State where incident took place.
| **`city`** |	City where incident took place. If the city is in a larger metropolitan area, that is indicated in parentheses.
| **`date`** |	Date incident took place.
| **`company`** |	App that gig worker was using at time of incident. An asterisk next to the company name indicates that the company says it hasn't found evidence this specific incident occurred on its platform. Incidents where a report indicates that a ride-hail driver was involved but does not specify which company they worked for are marked, "Unclear (Ride-hail)."
| **`carjacking_happened_via_the_app`** |	Whether the alleged assailant(s) hailed the driver through the app or if the incident happened randomly on the street, based on descriptions found in the sources. Marked "Yes," "No," or "Unclear."
| **`driver_deceased`** |	Whether the driver was killed as a result of the incident.
| **`source`** |	Where information was gathered to confirm incident.
| **`additional_sources`** |	Additional confirmation of the incident.

NOTE: The description of `company` was updated in July 2022 for further clarity.
