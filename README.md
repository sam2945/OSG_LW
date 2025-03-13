## Large Wood Accumualtion on the River Isonzo ##
This ShinyApp visualizes **Large Wood (LW) accumulation risks** in river systems using QGIS analysis results in R studio. 
The project identifies bridges at risk of LW blockages along the **River Isonzo**, 
highlighting mitigation sites based on spatial heatmaps and distance analysis. 

The analsyis is based on and includes:
- Bing imagery
- Heatmaps, bridges, Distance to Nearest Bridge and Large Wood Catchers
- It includes some raster layers store as tifs that include slope aspect and flow accumulation
- **The Mouseover feature is known to be able to run once but on a second run R studio crashes necessitating a restart**

## To start ##
Download and unzip the shiny file. Then open RStudio and navigate to the folder where the unzipped files are located. Open each script, install all the packages line by line and call the packages first. Then run the Global and UI scripts then the Server (ignore the error about *object 'output' not found*) and save them. Finally launch the shiny app and ignore the warnigns about colour. 

