# Fire Scars False Color Visualization 

<!-- <p align="center">
  <img src="image/image.png" alt="Map making" width="600">
</p> -->

## About 

This repository contains the materials for the [fourth homework assignment](https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4-palisades-eaton-fires.html) for [EDS 223: Geospatial Analysis and Remote Sensing](https://bren.ucsb.edu/courses/eds-220), a course that is part of the Master of Environmental Data Science program completed at the Bren School of Environmental Science and Management.

The homework assignment focuses on the environmental injustice of a location in the U.S. For this assignment, 


In early January 2025, the Eaton Fire and Palisades Fire erupted nearly simultaneously in the foothills and coastal wildland-urban interface zones of Los Angeles County, fueled by powerful Santa Ana winds. Together, they devastated thousands of homes, displaced tens of thousands of residents, and inflicted severe ecological and infrastructural damage.

False color imagery, created using satellite data from instruments like Landsat, is a useful tool for monitoring wildfire impacts. By assigning infrared bands to visible colors, these images highlight vegetation health, burn severity, and the extent of fire scars. This approach helps researchers and land managers assess recovery efforts, identify high-risk areas, and plan restoration strategies.

In this task, you will create a false color image of the Eaton and Palisades Fires using remote sensing data, highlighting the fire scar and exploring how coding and data visualization support environmental monitoring.


## Repository Structure

```
eds220-hwk4
├── data
│   └── landsat8-2025-02-23-palisades-eaton.nc
├── hwk4-task2-false-color-hernandez.ipynb
├── image
├── LICENSE
└── README.md

```

The `data` folder contains the data from `landsat8` as well as the fire perimeter which represent both `Palisades` and `Eaton`. The ipynb that contains the code is called `hwk4-task2-false-color-hernandez.ipynb`.

## Data

The `landsat8` data was given by the professor in google drive, but can accessed through [Microsoft Planetary Computer data catalog](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2).

The data for the `Palisades` can be downloaded directly [here](https://hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025/explore?layer=1&location=34.133841%2C-118.349462%2C10) and `Eaton` data [here](https://hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025/explore?layer=0&location=32.162108%2C-115.753942%2C7). Both were found using Google search with the first results titled, Palisades and Eaton Dissolved Fire Perimeters (2025), which is housed on [ArcGISHub](https://hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about).




## References