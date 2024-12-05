# Thomas Fire Analysis

Kimberlee Wong - December 4, 2024

## About

This repository includes two notebooks. Each notebook has the vital steps that were taken in order to get to the final product of a blog post that explores the region that was affected by the 2017 Thomas Fire. The hwk2-task3-aqi-wong.ipynb notebook has the steps taken to use AQI data provided by the EPA to create a graph that visualized the AQI in the county of Santa Barbara for the years 2017 and 2018. The hwk4-task2-false-color-wong.ipynb notebook has the code that was used to visualize the landsat data and overlay the perimeter on top. There is a data folder that  includes the Thomas Fire boundary that was made and the AQI data. The landsat data is accesible through the server.  

The following analysis was done in two-fold. Its purpose is to get a better understanding of the 2017 Thomas Fire that affected Ventura and Santa Barbara Counties. The first part shows the process of producing a graph that shows how the average air quality was affected, and the second part visualizes the region of fire through a false imagery map.

![image](https://github.com/user-attachments/assets/959812ec-8bf3-4a87-b1f8-e3de545e649b)

An image of the 2017 Thomas Fire, as seen over the Santa Barbara cityscape on Dec. 17, 2017. 

## Repository Structure
```
thomas_fire_analysis
│
├── README.md                     
├── hwk4-task2-false-color-wong.ipynb
├── hwk2-task3-aqi-wong.ipynb                       
├── .gitignore
├── thomas-fire-blog.ipynb                  
│
├── data/                       
│   ├── thomas_fire_boundary.cpg
│   ├── thomas_fire_boundary.dbf
│   ├── thomas_fire_boundary.prj
│   ├── thomas_fire_boundary.shp
│   ├── thomas_fire_boundary.shx
```

## Data
The landsat data comes from Microsoft Planetary Computer Data Catalogue, and it is a simplified collection of colored bands. It was processed to remove data outside land and coarsen the spatial resolution. It is not included in this repo, for it is housed in the server.

The Thomas Fire boundary was created by filtering a California Fire perimeter file available from the US Government Data Catalogue.

The AQI (Air Quality Index) data was created by the US EPA (Environmental Protection Agency), and was filtered down to Santa Barbara County.



## References

AQI Data: https://aqs.epa.gov/aqsweb/airdata (Accessed October, 2024)

Data.gov Data Catalogue, California Fire Perimeters (all) [Data file] Available from: https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436. Access date: November, 2024.

Hamm, K. (2017, December 14). Closing schools and moving finals due to Thomas Fire. The Santa Barbara Independent. https://www.independent.com/2017/12/13/closing-schools-and-moving-finals-due-thomas-fire/ 

Microsoft Planetary Computer Data Catalogue, Landsat collection 2 Level-2 [Data file] Available from: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. Access date: November 22, 2024.

Assignment came from UCSB Masters of Environmental Data Science class, EDS 220 - Working with Environmental Data Science. Class is taught by Carmen Galaz Garcia.


