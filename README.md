# Historic Redlining in LA County and Its Impact on Avian Biodiversity.

#### By Amanda G. Overbye

The purpose of this project is to a data analysis and HOLC areas in LA County, CA and how they relate to avian biodiversity.

### Skills Used

This repository uses the following skills:

**Data Handling and Cleaning**

- Loading and filtering large datasets using dplyr and sf. 
- Managing and transforming coordinate reference systems (CRS).

**Geospatial Analysis**

- Working with shapefiles and bounding boxes. 
- Joining spatial datasets (st_join, st_intersects).

**Data Visualization**

- Creating thematic maps with tmap. 
- Generating plots and charts using ggplot2.

**Automation and Functions**

- Writing reusable functions to check CRS compatibility.
- Summarizing data with group_by, summarise, and calculating percentages. 
- Identifying patterns and trends in demographic and biodiversity data.

### Repository 

``` bash
Redlining_and_Biodiversity
│   README.md
|   redlining_biodiversity_la.Rproj
|   redlining_biodiversity_la.html
|   redlining_biodiversity_la.qmd
|   .gitignore
```

### Data

-   **EJScreen**

    The data is located in the file ejscreen/EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb and sourced from the U.S. EPA. It provides environmental and demographic data at the Census block group level.

-   **HOLC Redlining**

    The file mapping-inequality/mapping-inequality-los-angeles.json contains digitized HOLC grade maps for Los Angeles, sourced from the Mapping Inequality Project at the University of Richmond.

-   **Biodiversity Observations**

    The data is contained in gbif-birds-LA.shp and sourced from the Global Biodiversity Information Facility (GBIF). It includes bird observation data about location, date, and what species was observed.

**References**

Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nature Human Behaviour, 1-9

GBIF.org, gbif-birds-LA dataset

Robert K. Nelson, LaDale Winling, Richard Marciano, Nathan Connolly, et al., “Mapping Inequality,” American Panorama, ed.Robert K. Nelson and Edward L. Ayers, accessed October 24, 2023

U.S. Environmental Protection Agency (EPA), 2024. EJScreen Technical Documentation, accessed October 24, 2023
