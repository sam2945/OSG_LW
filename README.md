This ShinyApp visualizes **Large Wood (LW) accumulation risks** in river systems using QGIS analysis results in R studio. 
The project identifies bridges at risk of LW blockages along the **River Isonzo**, 
highlighting mitigation sites based on spatial heatmaps and distance analysis. 
With large portions of the script provided by  Dieg
Practical 6 for GEOM184 - Open Source GIS         ##
##                      27/02/2025                             ##
##                  Creating a ShinyApp                        ##
##                        Global.R                             ##
##        code by Diego Panici (d.panici@exeter.ac.uk) 

The analsyis is based on and includes:
- Bing imagery
- Heatmaps, bridges, Distance to Nearest Bridge and Large Wood Catchers
- It includes some raster layers store as tifs that include slope aspect and flow accumulation
- **The Mouseover feature is known to be able to run once but on a second run R studio crashes necessitating a restart**
