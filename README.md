![Header image for the Foundations of Mapping workshop](https://github.com/goforanna/mappingfoundations/blob/15e8df4f4e17c618356993067ceb90906882a5ce/images/Foundationsheader.png)

Mapping is a powerful way to analyze, visualize, and explore spatial data. A Geographic Information System (GIS) is a mapping technology that allows users to analyze spatial data and produce cartographic visualizations. This workshop will teach you the foundational concepts of GIS that are applicable across platforms. No prior experience necessary

In this workshop, you will:
- Become familiar with the uses of cartography and spatial analysis
- Identify fundamental mapping components
- Distinguish between different forms of spatial data
- Recognize some of the core ethical considerations of mapmaking.
- Practice formulating spatial research questions

---

<p align="center">This workshop is estimated to take you 45 minutes to complete.</p><p align="center"><a href="sections/01-introduction-to-mapping.md">Get Started</a> →</p>

---

## Lessons

1. [Introduction to Mapping](sections/01-introduction-to-mapping.md)
2. [Mapping Tools](sections/02-mapping-tools.md)
3. [Ethics of Mapping](sections/03-ethics-of-mapping.md)
4. [Ethics of Mapping Continued: Questions to Consider](sections/04-ethics-of-mapping-continued-questions-to-consider.md)
5. [Making an Interactive Map: Introduction](sections/05-making-an-interactive-map-introduction.md)
6. [Combining Data Through a Spatial Join](sections/06-combining-data-through-a-spatial-join.md)
7. [Performing a Spatial Join](sections/07-performing-a-spatial-join.md)
8. [Exporting Data from QGIS](sections/08-exporting-data-from-qgis.md)
9. [Importing Data to ArcGIS Online](sections/09-importing-data-to-arcgis-online.md)
10. [Changing the Map Style](sections/10-changing-the-map-style.md)
11. [Configuring the Pop-up](sections/11-configuring-the-pop-up.md)
12. [Importing CSV file and Geocoding Addresses](sections/12-importing-csv-file-and-geocoding-addresses.md)
13. [Changing the Style of the Points Layer](sections/13-changing-the-style-of-the-points-layer.md)
14. [Formatting the Pop-ups for the Protest Locations](sections/14-formatting-the-pop-ups-for-the-protest-locations.md)
15. [Formatting the Legend](sections/15-formatting-the-legend.md)
16. [Saving and Sharing Your Map](sections/16-saving-and-sharing-your-map.md)

---

## Before you get started

If you do not have experience or basic knowledge of the following workshops, you may want to look into those before you start with Introduction to Mapping:

- [Data Literacies](https://github.com/DHRI-Curriculum/data-literacies) (recommended) In order to have a better understanding of the data formats we handle in this workshop, if you don't already have a foundational understanding of data formats and types, you can start by walking through our Data Literacies workshop.
- [Install QGIS](https://github.com/DHRI-Curriculum/install/blob/main/sections/qgis.md) (required) To complete this workshop you will need to install QGIS. Step by step installation instructions are available here.

### Ethical Considerations

Before you start the Introduction to Mapping workshop, we want to remind you of some ethical considerations to take into account when you read through the lessons of this workshop:

Starting from figuring out how to represent a 3D reality on a 2D plane, there are countless subjective decisions that every mapmaker must make, whether they are conscious of it or not. Mapmakers need to decide what data to represent and what to leave out. They also need to decide how to aggregate, categorize, project, combine, and visualize the data. All of these decisions will influence the story that the map tells. Additionally, as a critical tool of Western colonialism and imperialism, maps wield great authority. As mapmakers, it's essential to be conscious of this history not to reproduce harmful power dynamics through mapmaking. Once something is visualized in the form of a map, it is often understood as a Truth representation of reality. Therefore, mapmakers have an important responsibility to be as honest and transparent as possible. Since the 1980's, there have been two emerging disciplines in academia—critical cartography and feminist GIS—that have brought to light many of the harmful applications of mapping. Rather than reject mapping, they have made significant contributions to the field of GIS and mapping, such as counter mapping, sketch mapping, participatory mapping, qualitative GIS and 3D body-mapping. The following readings will introduce you to some of the fundamental insights from critical cartography and feminist GIS that you can integrate into your mapping journey. The reading list also includes modern-day counter mapping projects.

- Harley, J. B. (1989). [Deconstructing the map](https://quod.lib.umich.edu/p/passages/4761530.0003.008/--deconstructing-the-map?rgn=main;view=fulltext). _Cartographica: The international journal for geographic information and geovisualization_, 26(2), 1-20. This is a classic text by Brian Harley – one of the first Foucauldian analyses of mapping.
- Pavlovskaya, M., & Martin, K. S. (2007). [Feminism and geographic information systems: From a missing object to a mapping subject](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1749-8198.2007.00028.x). _Geography Compass_, 1(3), 583-606. This article makes the case for feminist GIS. 
- Pavlovskaya, M. (2002) [Mapping urban change and changing GIS: Other views of economic restructuring](https://www.researchgate.net/publication/240107165_Mapping_Urban_Change_and_Changing_GIS_Other_views_of_economic_restructuring). _Gender, place and culture: A journal of feminist geography_ 9, 281-289. This study demonstrates how GIS can be part of a critical and feminist analysis of economic development. 
- Kwan, M. P. (2008). [From oral histories to visual narratives: Re-presenting the post-September 11 experiences of the Muslim women in the USA](http://meipokwan.org/Paper/SCG_2008.pdf). _Social & Cultural Geography_, 9(6), 653-669. This study by a feminist GIS scholar uses 3D body maps to challenge the 2D limitations of most maps. She also combines interviews and survey data to create the visualizations. 
- [Counter Mapping: Zuni Maps](https://emergencemagazine.org/feature/counter-mapping/). The indigenous Zuni people describe their mapping project and the ways it challenges Western modes of mapping.

### Pre-reading suggestions

Before you start the Introduction to Mapping workshop, you may want to read a couple of our pre-reading suggestions:

- [Finding the Right Tools for Mapping](https://digitalfellows.commons.gc.cuny.edu/2019/06/03/finding-the-right-tools-for-mapping/)
- [Finding Data for Mapping: Tips and Tricks](https://digitalfellows.commons.gc.cuny.edu/2018/11/24/finding-data-for-mapping-tips-and-tricks/)
- [Create A Rich Multimedia Narrative with ESRI Story Maps](https://digitalfellows.commons.gc.cuny.edu/2019/02/12/create-a-rich-multimedia-narrative-with-esri-story-maps/)

### Projects that use these skills

You may also want to check out a couple of projects that use the skills discussed in this workshop:

- [Visualizing NEH Open Data](https://digitalfellows.commons.gc.cuny.edu/2017/04/04/visualizing-neh-open-data/)
- [Mapping Occupation](https://gcdi.commons.gc.cuny.edu/mapping-occupation-the-union-army-and-the-meaning-of-reconstruction/)
- [NYC’s Worst Evictors](https://www.worstevictorsnyc.org/map/)
- [Torn Apart/Separados](http://xpmethod.columbia.edu/torn-apart/volume/2/index)
- [Native Land](https://native-land.ca/)
- [COVID Mapping Projects](https://digitalfellows.commons.gc.cuny.edu/2020/11/02/mapping-the-effects-of-covid-19/)

---

<p align="center"><a href="sections/01-introduction-to-mapping.md">Get Started</a> →</p>

---

## Acknowledgements

This workshop is the result of a collaborative effort of a team of people, mostly involved presently or in the past, with the Graduate Center's Digital Initiatives. If you want to see statistics for contributions to this workshop, you can do so [here](https://www.github.com/DHRI-Curriculum/mapping/graphs/contributors). This is a list of all the contributors:

- Current Author: [Olivia Ildefonso](https://oildefon.medium.com/)
- Past contributing author: [Javier Otero Peña](https://enviropsych.org/students/javier-otero-pena/)
- Editor: [Kalle Westerling](https://github.com/kallewesterling)
- Editor: [Dr. Lisa Rhody](https://github.com/lmrhody)

---

<sub>[Digital Research Institute (DRI) Curriculum](http://purl.org/dc/terms/) by [Graduate Center Digital Initiatives](https://gcdi.commons.gc.cuny.edu/) is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). Based on a work at <https://github.com/DHRI-Curriculum>. When sharing this material or derivative works, preserve this paragraph, changing only the title of the derivative work, or provide comparable attribution.</sub>

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)
