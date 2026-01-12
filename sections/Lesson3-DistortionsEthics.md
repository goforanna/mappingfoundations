# 'The Map is Not the Territory': Distortions, Decisions, and Ethics
Representing the real, 3D world in a contained, 2D display involves making choices and decisions that will necessarily be distortions of reality. At the most foundational level, every map begins with a lie--that the earth is flat. Any time you flatten a sphere you end up with distortion. This distortion worsens when the sphere isn’t a perfect sphere but is a kind of lumpy sphere--a geoid--like earth is. So when you flatten the earth into a **projection** you end up with some kind of distortion, no matter what. 

Distortion happens in four ways. **Shape** is distorted, **size** is distorted, the **direction** between point a to point b is distorted, and the **distance** between those points is distorted. To rectify this, cartographers have developed a myriad of different ways to project the earth onto a flat surface. These are called map projections. As a rule of thumb, each projection can preserve no more than two of the four distortions and usually is only applicable to different certain areas of the world at certain scales. 

For example, the Mercator Projection--the most famous and recognizable map projection--was originally developed for marine navigation across the Atlantic in the 16th century. The Mercator Projection preserves direction and distance near the equator at the cost of shape and size. See how at the world scale the Mercator Projection bloats the sizes and shapes of lands the further they are from the equator. Inappropriate and uninformed use of the Mercator Projection is how billions of people grew up thinking Greenland was the size of Africa.

 ![Mercator distortion example](https://github.com/goforanna/mappingfoundations/blob/946f33d93dbfce5f6c03ee5211ad0a01a0894665/images/mercatordistortion.mp4)
 
Beyond visual misrepresentation, inappropriate projections can mess with the accuracy of your spatial analysis. If your analysis involves measuring large distances in the United States, for example, using the Mercator projection will produce a different calculation than a projection that preserves area and distance like the Albers Equal Area Conic.  
![Distortion Example](https://github.com/goforanna/mappingfoundations/blob/946f33d93dbfce5f6c03ee5211ad0a01a0894665/images/distancedistortion.png)

### Knowledge Check
If you are making a map that shows how long it takes to walk to the nearest subway station in New York City, you should choose a map projection that preserves:

<Quiz>
- Size
- Distance*
- Direction
- Shape
</Quiz>

## Decisions and Ethics
So much of map-making is dependent on the positionality of the mapmaker and all of the subjective decisions that they must make when deciding what will be mapped, how the data will be manipulated, and how it will be visualized. Here are some questions to ask yourself as you begin to formulate your project:

- **What data should I use?** If you choose to use data that's already collected (e.g. Census data), are you using it because it's the easiest to access or because it's the most appropriate data to answer your research question? What are the limitations of using data that hasn't been collected or managed by you?
- **How should I classify the data?** What categories will you create? For example, if you are working with racial demographics, will you report on the categories such as Latinx, non-Latinx White, non-Latinx Black, Latinx White, Latinx Black, etc, or will you provide broader categories such as people of color and White? What are the implications of choosing more general or more particular categories?
- **At what resolution or scale should the data be aggregated?** If you are studying a phenomena at the neighborhood level, how do you define the boundaries of a neighborhood? Is it based on the school district, the Census Designated Place (CDP), the voting district, or maybe a boundary that doesn't have a formal delineation, such as a sense of community among people?
- **What projection should I use?** What kinds of distortion is it important for you to minimize? What are the consequences of sizes, shapes, distances, and directional aspects of your data being inaccurate?
- **How should my map be oriented?** Is it important that North be at the top of the map? What should be at the center of my map? 
- **What are the implications of aggregating the data at a certain scale?** For example, let's say you are studying the differences between urban and suburban areas. If you aggregate your data at the level of counties, what could be missing from that representation of the data? Is something happening at the level of the neighborhood or town that could prove useful to answer your research question? This is not to say that the smallest scales are always the best to work with, but rather to suggest that when we aggregate data, we need to be aware of what distinctions we are hiding in the process.
- **What colors and symbols should I use?** Should you represent a population in red or blue? Red normally signals something that is alarming, while blue is a more neutral color. These subjective cartographic design decisions greatly impact viewer's understanding of the map.

For more guiding questions on ethical decision making, please see ["Ethical Decision-Making"](https://serc.carleton.edu/geoethics/Decision-Making), a robust resource put together by the "Community of Earth Educators."

## Formulating a Spatial Research Question

Beginning with a well-framed spatial question about the problem or phenomena you're interested in is key to making a compelling map or producing informative results. Focus on the spatial relationships between research variables or the spatial characteristics of a single variable. 

The key is to start with a simple, answerable question. It's often the case that a seemingly simple and boring question can lead to bigger and more interesting questions. However, if you start with the big, complex question, it can be difficult to parse into concrete spatial relationships. So start small and then build on your question, if needed. 

Some spatial questions might take the form of:
- *How many are in an area?*
- *Which sites meet my criteria?*
- *What are the characteristics of an area?*
- *How is it distributed?*
- *What is near what?*
- *What is on top of what?*
- *How is it related?*
It's likely that your question will involve a combination of these formats, and its even more likely that exploration and experimentation during the map-making process will answer questions you hadn't thought to ask. 
