# VisualColoc package for colocalization analysis and visualization using electron microscopy (EM) data and particle coordinates
This tool enables effective visualization of Pearson's Colocalization Coefficient (between two particle types) in a form of a heatmap overlayed on the EM image. The package would be useful for the projects that target immunolabeling and are aiming for particle colocalization analysis and its effective visualization.

The example of an output data provided below:
![UA03_overlayed_(128, 128)_4_6](https://user-images.githubusercontent.com/113347533/189636416-282bffa5-71a3-4214-8357-383f33508b5e.png)
# Requirements
\list Python 3.4 or later
\ list Image J Fiji or any other kind of software that allows particle detection or coordinate identification 

The code uses 2 or more CSV files with particle coordinates as input files. For this project ImageJ Fiji software was used to manually find and indentify postions of particles, the coordinates were saved in 2 CSV files corresponding to each particle type. CSV files are preferrably ro be stored in the same folder as the EM image analysed. 

