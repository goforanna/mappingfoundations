# Components of a Map
In order to make a map, we need spatial data. **Spatial data** (also called **geospatial data**) refers to information about the **location, shape, and size** of objects or phenomena on the Earth's surface, and the relationships between them. In the real world and on globes, this data is often represented with geographic coordinates (latitude and longitude). But on flat surfaces, this data is represented with cartesian, or projected, coordinates (x,y coordinates). 
![Coordinate Systems](https://github.com/goforanna/mappingfoundations/blob/946f33d93dbfce5f6c03ee5211ad0a01a0894665/images/CoordinateSystems.png)

### Knowledge Check
What spatial data is needed to make a map like this one?
![Map of Walking Distance to Subway](https://github.com/goforanna/mappingfoundations/blob/946f33d93dbfce5f6c03ee5211ad0a01a0894665/images/subwaywalkingdistance.png)

<Quiz>
- Locations of NYC Roads*
- Shape and location of New York City*
- Shape of NYC Water Features
- Locations of NYC Subway Stations*
</Quiz>

## Types of Spatial Data: Vector and Raster 
There are two major file types of spatial data: **vector datasets** and **raster datasets**. Vector data is the most common type of GIS data. Vector data represents spatial data as collections of points, each with a given coordinate. Those points are then grouped into **features**. Before we talk more about vector data, we'll briefly touch on raster data. Raster data represents spatial data as a matrix of cells (or pixels) that each contain an attribute value (like elevation or temperature). Satellite imagery, jpeg scans of historical maps, or digital elevation models are all examples of raster data. Unlike vector data, the resolution is fixed in raster data, and the size of each pixel determines the level of detail in the map. Smaller pixels mean higher resolution, and larger pixels mean lower resolution. 

![Vector Data Versus Raster Data](https://github.com/goforanna/mappingfoundations/blob/946f33d93dbfce5f6c03ee5211ad0a01a0894665/images/rastervector.jpeg)

## Vector Data: Features and Attributes
Vector datasets represent spatial data as features. **Features** are the fundamental building blocks of map creation and are **displayed as points, lines, or polygons**. In the NYC Distance-to-Subway map from earlier, subway stations, streets, and the city boundary are the features of the map. 
- Subway stations are represented as point features, with no length or area.
- Streets are represented as line features, with length but no area.
- The city boundary is represented as a polygon, with both length and area. 

Features can also hold relevant non-spatial data, called **attribute data**. While spatial data represents the location, shape, and size of geographic features, **attribute data** provides more detailed, non-spatial information about those features, like subway station names (for points), street names (for lines), or populations (for polygons). Attribute data can be visually represented by changing the size, shape, or color of the feature (AKA the **symbology**), or by alphanumeric annotations. 

![Feature Types](https://github.com/goforanna/mappingfoundations/blob/946f33d93dbfce5f6c03ee5211ad0a01a0894665/images/featuretypes.gif)

## Vector Data: Layers and Feature Classes
GIS compiles and integrates data by layering different datasets on top of each other. These layers are called **feature classes**. Each feature class contains homogenous data, meaning that there is only one *kind* of feature in each feature class, whether its points, lines, or polygons, and the categories of attribute data are applicable to each feature within the feature class. For example, in the following image there are three feature classes. The street feature class contains line features, while the buildings and vegetation feature classes each contain polygon features. Each building is a polygon feature within the buildings feature class, and each feature contains attribute data like building type, address, number of floors, or hours of operation. 

![Visualization of GIS Integration of Layers](https://github.com/goforanna/mappingfoundations/blob/946f33d93dbfce5f6c03ee5211ad0a01a0894665/images/GISIntegration.jpg)

### Knowledge Check
The following are all types of vector data except:

<Quiz>
- Points
- Pixels*
- Lines
- Polygons
- Cells*
</Quiz>
