# GLIMS Data for New Zealand Glaciers

This folder contains geographic information system (GIS) data related to glaciers in New Zealand, sourced from GLIMS. The data is categorized into line, point, and polygon files, representing different aspects of glacier boundaries and features. Additionally, a CSV file provides further details on glacier attributes.

## File Descriptions

- **`nz_glaciers_lines.*`**: These files contain line data for glaciers in various formats (`.cpg`, `.dbf`, `.prj`, `.shp`, `.shx`) to represent linear features of the glaciers.
- **`nz_glaciers_points.*`**: These files contain point data for glaciers in various formats (`.cpg`, `.dbf`, `.prj`, `.shp`, `.shx`) to represent point features of the glaciers.
- **`nz_glaciers_polygons.*`**: These files contain polygon data for glaciers in various formats (`.cpg`, `.dbf`, `.prj`, `.shp`, `.shx`) to represent the polygonal boundaries of the glaciers.
- **`nz_glims_hypsometry_50.csv`**: This CSV file contains hypsometry data (area-elevation distribution) for New Zealand glaciers, providing further insights for analysis.

## File Format Information

- **`.shp`**: The main Shapefile that contains geometry data.
- **`.dbf`**: The attribute data associated with the shapes, stored in a dBASE format.
- **`.shx`**: The index file for the Shapefile, linking geometry and attribute data.
- **`.prj`**: The projection file that describes the coordinate system and map projection.
- **`.cpg`**: The file specifying character encoding for the Shapefile.
