# Stream-Network-Analysis-in-a-Watershed

Rivers and streams plays a natural border between different countries and political entities. Therefore, it is important to correctly understand and determine the actual major source of water and other characteristics of a watershed to correctly delineate the political boundary. As such, this project helps to figure out the actual political boundary between India and Nepal along the western border of Nepal. Here, the two different watershed namely, Limpiyadhura and Kalapani which lies at the boarder are compared in terms of Watershed Area, Stream Networks, Length of the Longest Stream, and Drainage Density and the watershed with higher values in all these parameters is determined as the major watershed meaning that the longest river/stream in this particular watershed represents the actual political boarder between Nepal and India.

This project uses Stahler Stream Order Method to compute the order of the streams and tributaries. Area of watersheds are computed after delineating the watersheds with respective pourpoints on DEM layer. The total lengths of the river/streams are computed in both actual and weighted terms - weights being the order number of the streams. Drainage Density is computed by dividing the total length of river/streams by total area of watershed. The same is done with weighted lengths. The result of both the cases is as follows:


![image](https://user-images.githubusercontent.com/114010808/235295620-2555e7bf-581e-496b-8292-1bf13a8e1334.png)

The result shows that Limpiyadhura is the major watershed with major watersource for the entire basin so the longest river/streams starting from the major source in Limpiyadhura watershed represents the actual natural border between Nepal and India. This means that the area of watershed on the right of this major river/stream falls under the entity of Nepal. This adds an area of 358.15 sq.km. to the uncorrected area of Nepal (147662.64 sq.km.) resulting in an area of 148020.79 sq.km. in total.

The data used for this project are obtained from following sources.

https://www.diva-gis.org/

https://earthexplorer.usgs.gov/
