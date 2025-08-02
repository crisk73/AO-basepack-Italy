# AO base pack Italy and Alps
This is a hi-res mesh XP12 compatible base package for AutoOrtho covering Italy and Alps.

The reason I made it is mainly because coastline is broken in the to date AO and ME base packages. Here I've applied XP12 water tech for bathymetry and coastlines look fine. The other reason is because I wanted to improve the Alps mesh. Patches are used for the main sloped airports (such as Courchevel).

I'd like to share those pre-built tiles to be used either with AO or ME and also to be further improved or additional areas to be created.

30m res mesh can be found here: [Coverage map viewfinderpanoramas.org](https://viewfinderpanoramas.org/dem1d.html) You need to manually copy elevation data files in each correct XX+XXX folder inside the Elevation_data folder in O4XP. Another good source of hi-res mesh is https://portal.opentopography.org/dataCatalog?group=global

Settings to pre-build tiles compatible with AO and ME are included. Remember to set skip_download and skip_converts to True in the O4XP App settings.

The release includes both the single pre-built tiles in case you want to edit them in Ortho4XP v1.40 and the consolidated package to be copied in the folder: ...\Custom Scenery\z_autoortho\scenery. Overwrite if asked.

If you intend to use it with XPlane Map Enhancement copy the files from “Earth nav data” and overwrite the files in the existing base package. Then copy the files from “textures” into “_textures” in the same base package. DON'T copy the files in the \terrain folder.
