# Svalbard catchment delineation

Data and code for delineating catchment boundaries on Svalbard.

**For catchment delineation, use Notebook 3** (notebooks 1 and 2 do not need re-running unless the input elevation data or pre-processing steps are changed.).

 * **Notebook 1** downloads raw data from the ArcticDEM server. The data are reprojected, merged and masked, then down-sampled to create versions with 10, 20 and 40 m resolution.
   
 * **Notebook 2** performs "terrain conditioning": vector streams and lakes are "burned in", pits are filled, and grids of flow direction and accumulation created.

 * **Notebook 3** reads an Excel file with outlet co-ordinates and derives catchment boundaries for each outlet.