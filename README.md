![](images/eldgos02_b.jpg)
# Volcanoes
[íslenska](README_IS.md)  

*A volcanic eruption started at 20:45 GMT 19. March 2021 in the Geldingadalir valley at Fagradalsfjall, e. 'Beautiful valley mountain', on the Reykjanes peninsula, South-West Iceland. The eruption is ongoing.*

Models of Icelandic volcanoes for 3D printing of relief maps, molds for plaster casting and chocolate making. All data in this repository is free to use for educational, personal or commercial purposes. Please attribute either this repository or Geo-Vis lab of University of Iceland.





## Relief maps
[![](images/relief_map_c.jpg)](Relief_maps/)

STL files for 3D printing 15 x 15 cm relief map models at three zoom levels. See instructions and files in [Relief_maps](Relief_maps/) folder.

## Plaster casting
[![](images/plaster_of_paris_small_medium_c.jpg)](Molds_for_plaster_casting/)

STL files for 3D printing plaster of paris casting molds and accessories. Files and instructions in [Molds_for_plaster_casting](Molds_for_plaster_casting/) folder.  Timelapse instructional [YouTube video](http://www.youtube.com/watch?v=xSu4fhIfEEE) below.

[![](images/youtube01.jpg)](http://www.youtube.com/watch?v=xSu4fhIfEEE "Timelapse of plaster casting Fagradalsfjall")


## Chocolate molds
[![](images/chocolates_c.jpg)](Chocolate_molds/)

STL files for 3D printing molds for casting silicone molds for chocolate making. Files in [Chocolate_molds](Chocolate_molds/) folder. 



## GoogleEarth overview
[![](images/KLM_ref_c.jpg)](KLM_refererences/)

KLM files for loading into [Google Earth](https://earth.google.com/web/). Files and instructions in [KLM_refererences](KLM_refererences/) folder. 


## Slicing of STL files

3D models are prepared for printing in Ultimaker Cura configured for Crealty Ender Pro printer.  Important: Top and bottom thickness has been doubled from 0.8mm to 1.6mm. Top thickness needs to be increased or else elevation lines may misprint in 3D printer. If making plaster molds, bottom thickness also needs to be increased so the model does not deform when pressed to release from mold frame.

## 3D printing
For molds it may be worth it to print at highest resolution
possible. For example Crealty Ender 3 printer normal print quality is
0.2mm resolution, but at highest print quality the resolution is
0.12mm, resulting in increased detail and finer elevation
lines. However, casts print at 0.2mm produce starker detail and more
defined shadows.


## Credits

The Digital Elevation Model used here is based on the ArcticDEM dataset created from DigitalGlobe, Inc., imagery and funded under National Science Foundation awards 1043681, 1559691, and 1542736. The DEM was manually adjusted to remove errors and gaps in the data. 

STL files were created using [QGIS](https://qgis.org) software utilising the [DEMto3D](https://demto3d.com/en/) plugin. Slicing of 3D maps and mirroring of the inverted relief maps were realised in [Ultimaker
Cura](https://ultimaker.com/software/ultimaker-cura). Chocolate molds were created using [Blender](https://www.blender.org/).

See [Credits.md](Credits.md) file.


## Licence

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].



[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg




