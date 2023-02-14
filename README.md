# Focus on Hawaii

## Introduction
This project aims to investigate some economic parameters and soil organic matter in Oahu, Hawaii using simple analysis methods in R. The study will make use of maps to visualize the data and identify patterns and correlations. To accomplish this, I will utilize several R packages including tmap, sf, sp, rgdal and others to process, analyze, and display the data. These packages offer a range of functions for working with spatial data, including mapping, projection conversion, and data manipulation. By combining these tools, I hope to gain a comprehensive understanding of the relationship between economic parameters and soil organic matter in Oahu, Hawaii.

## Methods and analysis

When one wants to explore and visualize global data, the "World" dataset available in the R package tmap can prove to be a valuable resource. This dataset contains information on the political boundaries and attributes of countries and regions around the world. With the help of this dataset, researchers and analysts can generate maps and visualizations that reveal patterns and relationships within global data. The World dataset has been widely used in various fields, including economics, political science, and environmental studies. Its broad scope and accessibility make it a useful tool for anyone interested in examining global trends and patterns.

The "World" dataset available in the R package tmap is a spatial object that represents the political boundaries of countries and regions around the world. Specifically, it is a "SpatialPolygonsDataFrame," which means that it is made up of polygons that define the shapes of the various geographic entities and associated data that describes their attributes.

In addition to understanding the type of spatial object that the "World" dataset is, it is also important to consider its Coordinate Reference System (CRS). The CRS is a system that defines how geographic coordinates, such as latitude and longitude, are related to locations on the Earth's surface. The "World" dataset uses the WGS 84 datum, which is a widely used CRS that is based on the Earth's ellipsoid shape and has been adopted as a standard by the Global Positioning System (GPS). This allows analysts and researchers to accurately interpret and visualize the spatial information contained in the dataset.
