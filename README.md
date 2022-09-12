# VisualColoc package for colocalization analysis and visualization using electron microscopy (EM) data and particle coordinates
This tool enables effective visualization of Pearson's Colocalization Coefficient (between two particle types) in a form of a heatmap overlayed on the EM image. The package would be useful for the projects that target immunolabeling and are aiming for particle colocalization analysis and its effective visualization.

The example of an output data provided below:


![for_github](https://user-images.githubusercontent.com/113347533/189658559-7509ce8b-70f6-408c-ab50-85de558eb75b.png)
# Requirements
- Python 3.4 or later
- Image J Fiji or any other kind of software that allows particle detection or coordinate identification 

The code uses 2 or more CSV files with particle coordinates as input files. For this project ImageJ Fiji software was used to manually find and indentify postions of particles, the coordinates were saved in 2 CSV files corresponding to each particle type. CSV files are preferrably ro be stored in the same folder as the EM image analysed. 

