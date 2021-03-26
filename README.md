# Volcanoes

Models of Icelandic volcanoes for 3D printing of relief maps and molds for plaster casting.  

An volcanic eruption started at 20:45 GMT 19. March 2021 in the Geldingadalir valley at Fagradalsfjall, e. 'Beautiful valley mountain', on the Reykjanes peninsula, South-West Iceland.

The Digital Elevation Model used here is based on the ArcticDEM dataset created from DigitalGlobe, Inc., imagery and funded under National Science Foundation awards 1043681, 1559691, and 1542736. The DEM was manually adjusted to remove errors and gaps in the data. STL files were created using QGIS software utilising the DEMto3D plugin. Slicing of 3D maps and mirroring of the inverted relief maps were realised in Ultimaker Cura.

## Relief map .stl files

### [Fagradalsfjall_largearea.stl](Fagradalsfjall_largearea.stl)
Description: 3D relief map of area around Fagradalsfjall. Area from North of Keilir, past Fagradalsfjall to shoreline.  
Size: 146.84mm x 146.84mm  
Vertical exaggeration: x 2.00  
Scale: 1:75000  

### [Fagradalsfjall_mediumarea.stl](Fagradalsfjall_mediumarea.stl)
Description: 3D relief map of Fagradalsfjall. Area encompassing all of Fagradalsfjall.  
Size: 146.84mm x 146.84mm   
Vertical exaggeration: x 1.5  
Scale: 1:40907  

### [Fagradalsfjall_smallarea.stl](Fagradalsfjall_smallarea.stl)
Description: 3D relief map of area of Fagradalsfjall eruption. Closeup of area.    
Size: 146.84mm x 146.84mm   
Vertical exaggeration: x 1.25  
Scale: 1:20455  

## GoogleEarth overview
The following image shows an overview of the three zoom areas created for the Fagradalsfjall eruption site. Each rectange relates to the KML file available for download in this repository to allow an exploration of the area in GoogleEarth and other GIS tools.

[Small area](KLM_refererences/Fagradalsfjall_smallarea_GoogleEarthreferenceframe.kml)  
[Medium area](KLM_refererences/Fagradalsfjall_mediumarea_GoogleEarthreferenceframe.kml)  
[Large area](KLM_refererences/Fagradalsfjall_largearea_GoogleEarthreferenceframe.kml)

![](images/Fagradalsfjall_GoogleEarthReference.jpg)


## Slicing of STL files
3D models are prepared for printing in Ultimaker Cura configured for Crealty Ender Pro printer.  Important: Top thickness has been doubled from 0.8mm to 1.6mm. 

## Plaster casting
See instructions and files in [Molds_for_plaster_casting](Molds_for_plaster_casting/) folder.


## Licence

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].



[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg




