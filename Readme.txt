This folder contains all of the analysis for the Bohrer & Larson 2022 manuscript. 
It contains the jupyter lab notebooks used to perform the analysis as well as some of the analyzed data. 

Note that all the raw data within this manuscript is within the file: chromosome21.tsv and is from Su et al. 2020.

The notebook Organize_Data.ipynb, is analysis code that organizes the data and quantifies all of the distances between the different loci as well as the corresponding transcription state of the different genes. Note, this was not computationally optimized for this project and was organized in such a way for efficent parrallel computation. If you do not have access to a computational cluster you may have to rewrite the code to run it in a timely manner. The output of this notebook will generate the Linked_Trajectories, Transcription_Trajectories and the Distances folders. 

The notebook Analysis_1.ipynb contains the analysis and code to make all of the subfigures (within reason) of Fig. 1. Again note this was not written for speed and you may want to use a computer cluster on certain points. The results of this code will generate the folders Single_Median, 

