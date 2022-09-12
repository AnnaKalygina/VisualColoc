# VisualColoc package for colocalization analysis and visualization using electron microscopy (EM) data and particle coordinates
This tool enables effective visualization of Pearson's Colocalization Coefficient (PCC) in a form of a heatmap overlayed on the EM image. The package would be useful for the projects that target immunolabeling and are aiming for particle colocalization analysis and its effective visualization. As a result the image is split by a sliding window and an individual colocalisation coefficient is attributed to each descrete frame. This approach allows to scan for the colocalization hotspots in any image data and calcualte and average PCC for an image. 

The example of an output data provided below. :


# Requirements
- Python 3.4 or later
- Image J Fiji or any other kind of software that allows particle detection or coordinate identification 

The code uses 2 or more CSV files with particle coordinates as input data. For this project ImageJ Fiji software was used to manually find and indentify postions of particles, the coordinates were saved in 2 CSV files corresponding to each particle type. CSV files are preferrably to be stored in the same folder as the EM image analysed. 

# Quick Start
1. Prepare input files by generating a .csv file containing x,y coordinates. In case you have 2 types of particles, generate 2 tables and specify the particle type in additional column. Hence, a table must contain 4 columns: [index, x coordinate, y coordinate, particle type]. The recommended software for particle recognition is ImageJ Fiji with "Click Coordinates Tool" macro preinstalled from: https://imagej.nih.gov/ij/macros/tools/ClickCoordinatesTool.txt

2. Before running code make sure you know dimensions of an analysed image. You can also choose a sliding window size and a step size depending on a format of a picture. 


# Output Files
