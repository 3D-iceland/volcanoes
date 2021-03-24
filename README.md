# volcanoes

Models of Icelandic volcanoes for 3D printing of relief maps and molds for plaster casting.  

An volcanic eruption started at 20:45 GMT 19. March 2021 in the Geldingadalir valley at Fagradalsfjall, e. 'Beautiful valley mountain', on the Reykjanes peninsula, South-West Iceland.

The Digital Elevation Model used here is based on the ArcticDEM dataset created from DigitalGlobe, Inc., imagery and funded under National Science Foundation awards 1043681, 1559691, and 1542736. The DEM was manually adjusted to remove errors and gaps in the data. STL files were created using QGIS software utilising the DEMto3D plugin. Slicing of 3D maps and mirroring of the inverted relief maps were realised in Ultimaker Cura.

## Files

### Fagradalsfjall_largearea.stl
Description: 3D relief map of area around Fagradalsfjall. Area from North of Keilir, past Fagradalsfjall to shoreline.  
Size: 146.84mm x 146.84mm  
Vertical exaggeration: x 2.00  
Scale: 1:75000  

### Fagradalsfjall_largearea_inverted.stl
Description: Inverted 3D relief map of area around Fagradalsfjall for casting. Area from North of Keilir, past Fagradalsfjall to shoreline.  
Size: 146.84mm x 146.84mm    
Vertical exaggeration: x 2.00    
Scale: 1:75000

### Fagradalsfjall_mediumarea.stl
Description: 3D relief map of Fagradalsfjall. Area encompassing all of Fagradalsfjall.  
Size: 146.84mm x 146.84mm   
Vertical exaggeration: x 1.5  
Scale: 1:40907  

### Fagradalsfjall_mediumarea_inverted.stl
Description: Inverted relief map of Fagradalsfjall for casting. Area encompassing all of Fagradalsfjall.  
Size: 146.84mm x 146.84mm   
Vertical exaggeration: x 1.5  
Scale: 1:40907  


### Fagradalsfjall_smallarea.stl
Description: 3D relief map of area of Fagradalsfjall eruption for casting. Closeup of area.    
Size: 146.84mm x 146.84mm   
Vertical exaggeration: x 1.25  
Scale: 1:20455  

### Fagradalsfjall_smallarea_inverted.stl
Description: Inverted 3D relief map of area of Fagradalsfjall eruption for casting. Closeup of area.   
Size: 146.84mm x 146.84mm   
Vertical exaggeration: x 1.25   
Scale: 1:20455

### Mold_frame_1piece_146_84mm.stl
Description: Mold frame for casting relief maps. Single piece mold frame. Fits only models 146.84mm x 146.84mm.

### Mold_frame_4piece.stl
Description: Mold frame for casting relief maps. Four pieces needed to create a frame.  Fits various sized models. Pieces are fastened together with clamps/clothes pins.

### Wall_mount_10mm_impression.stl
Description: Object to create an 4mm x 30mm impression into back of plaster cast for hanging on wall. 10mm deep from top of mold frame. 

### Wall_mount_15mm_impression.stl
Description: Object to create an 4mm x 30mm impression into back of plaster cast for hanging on wall. 15mm deep from top of mold frame. 

### Wall_mount_20mm_impression.stl
Description: Object to create an 4mm x 30mm impression into back of plaster cast for hanging on wall. 20mm deep from top of mold frame. 


## GoogleEarth overview
The following image shows an overview of the three zoom areas created for the Fagradalsfjall eruption site. Each rectange relates to the KML file available for download in this repository to allow an exploration of the area in GoogleEarth and other GIS tools.

![](images/Fagradalsfjall_GoogleEarthReference.jpg)

## Slicing of STL files
3D models are prepared for printing in Ultimaker Cura configured for Crealty Ender Pro printer.  Important: Top thickness has been doubled from 0.8mm to 1.6mm. 

## Mold casting

1. Prepare everything beforehand. Have paper towels on hand.
2. Oil the form. You can use any cooking oil. Take care to dab excess oil from deep depressions or your mountain peaks will become flat. Oil the sides and also if you plan to make a wall mount depression oil that object too.
3. Assemble the mold. Take note to orient the mold so that North points away from you.
4. Weigh out water and plaster. Use gloves and a mask. Plaster is a very fine dust and you do not want to breathe it in. For one kg of water there should be 1.5 kg plaster added. Water should be cold. The colder the water is the more time you have to manipulate the plaster. To fill one mold use 300g water against 450g plaster. Weigh them out separately.
5. Pour water into a big enough plastic container, one preferably not too rigid to to make it easier to remove excess plaster once it is hardened. Never pour unhardened plaster into the sink or it will clog your drains. Distribute plaster powder over the surface of water in even thin layers and let it sink. When islands of plaster start to form on the surface the mixture should be thick enough. You do not need to use all the plaster powder. Let the mixture sit for 2-5 minutes, then mix with a gloved hand. Using your hands makes for less air bubbles. Mix for a little while until mixture is evenly dense. Knock the container to the table to remove excess air bubbles from mixture.
6. Pour in a single spot the plaster mixture. Knock the table to let the mixture settle evenly and remove air bubbles. If the mixture is good, the surface (back side of cast) should be flat.
7. If you use wall mounts, lay the wall mount depression on top of the mold where cast should hang on making sure it is level.
8. Wait for 30-60 minutes.
9. Remove mold, sides first, then top. The mold should come off easily. If it doesn‘t, give it more time. As a last resort you can wedge the top off with a flat tool, but this may leave an impression.
10. Discard excess hardened plaster. Clean mold pieces in water. Important! Do not use too hot water or the PLA plastic will warp/shrink.

![](images/Mold_assembly.jpg)

## Licence

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].



[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg




