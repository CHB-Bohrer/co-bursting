This folder contains all of the analysis for the Bohrer & Larson 2022 manuscript. 
It contains the jupyter lab notebooks used to perform the analysis as well as some of the analyzed data. 

Note that all the raw data within this manuscript is within the file: chromosome21.tsv and is from Su et al. 2020.
To download all prerun analysis please aditionally look to https://www.dropbox.com/sh/t14bisno1hj0vk2/AAB8oMYogcF7PKsVOJs45dn3a?dl=0  

The notebook Organize_Data.ipynb, is analysis code that organizes the data and quantifies all of the distances between the different loci as well as the corresponding transcription state of the different genes. Note, this was not computationally optimized for this project and was organized in such a way for efficent parrallel computation. If you do not have access to a computational cluster you may have to rewrite the code to run it in a timely manner. The output of this notebook will generate various folders with the Linked_Trajectories, Transcription_Trajectories and the Distances folders. All of this data can be obtained with the following link: https://www.dropbox.com/sh/t14bisno1hj0vk2/AAB8oMYogcF7PKsVOJs45dn3a?dl=0 
If you have any issues please email bohrerch@nih.gov

The notebook Analysis_1.ipynb contains the analysis and code to make all of the subfigures (within reason) of Fig. 1. Again note this was not written for speed and you may want to use a computer cluster on certain points. The results of this code will generate various folders stored within the Dropbox folder. There is also a pdf of this if you do not have python notebooks so you can look at the analysis independently. https://www.dropbox.com/sh/t14bisno1hj0vk2/AAB8oMYogcF7PKsVOJs45dn3a?dl=0 

The notebook Analysis_2.ipynb contains the analysis and code to make all of the subfigures (within reason) of Fig. 2. Again note this was not written for speed and you may want to use a computer cluster on certain points. The results of this code will generate various folders stored within the Dropbox folder. There is also a pdf of this if you do not have python notebooks so you can look at the analysis independently. https://www.dropbox.com/sh/t14bisno1hj0vk2/AAB8oMYogcF7PKsVOJs45dn3a?dl=0 

The notebook Analysis_3.ipynb contains the analysis and code to make all of the subfigures (within reason) of Fig. 3. Again note this was not written for speed and you may want to use a computer cluster on certain points. The results of this code will generate various folders stored within the Dropbox folder. There is also a pdf of this if you do not have python notebooks so you can look at the analysis independently. https://www.dropbox.com/sh/t14bisno1hj0vk2/AAB8oMYogcF7PKsVOJs45dn3a?dl=0 

The notebook Analysis_4.ipynb contains the analysis and code to make all of the subfigures (within reason) of Fig. 4. Again note this was not written for speed and you may want to use a computer cluster on certain points. The results of this code will generate various folders stored within the Dropbox folder. There is also a pdf of this if you do not have python notebooks so you can look at the analysis independently. 

There is an additional notebook called live_cell_analysis.ipynb and there is an additional folder called live cell analysis. This folder contains the TFF1 data of Joseph Rodriguez et al. Cell. 2019. 