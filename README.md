# Fire Scars False Color Visualization 

<p align="center">
  <img src="image/image.avif" alt="remote sensing and fire" width="600">
</p>

## About 

This repository contains the materials for the [fourth homework assignment](https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4-palisades-eaton-fires.html) for [EDS 220: Working with Environmental Datasets](https://bren.ucsb.edu/courses/eds-220), a course that is part of the Master of Environmental Data Science program completed at the Bren School of Environmental Science and Management.

Satellite data from instruments (E.g. Landsat) are used to create false color imagery by assigning infrared bands to visible colors which highight important aspects like vegetation health, burn severity, and the extent of fire scars that assist researchers and land managers to asses recovery effotrs, identify high-risk areas, and plan restoration strategies.

The homework assignment focuses on the Palisades and Eaton fires, foothill and coastal wildland-urban zones in Los Angeles County, that occured almost simultaneously around the start of January in 2025. From the two fires, thousands of homes were destroyed and displaced tens of thousands of residents as well as inflicing ecological and infrastructural damage.

For this assignment, the final output should be a false color image of the Eaton and Palisades fire through remote sensing data highlighting the fire scar. The importance of the assignment is to explore how data visualization and coding support environemental monitoring.

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

Microsoft Planetary Computer. Planetary Computer (2025). (n.d.). https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2 

Palisades and Eaton Dissolved Fire Perimeters (2025). ArcGIS Hub. (n.d.). https://hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c 