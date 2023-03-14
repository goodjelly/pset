# pset
a new repo for the pset4

Overview

this repo contains data sets from MS data of crab urine (Poulin et al. https://www.pnas.org/doi/abs/10.1073/pnas.1713901115).
The filed in Code will corresponds to their project stage-for now, it has one file for the pset 4. 

Y_X_pset4.py simply organizes the data file into dataframes that simplifies our analysis process.
generates a single bar plot that shows the top 10 chemicals with the higest peak from th negative mode of the MS data. 
All packages are conventional pandas, matplotlib or numpy packages. 

Data

this data is reported by Poulin et al., after they organized the MS data from 6 crabs (MC and OB are ommited in the MS). 
This data set includes the chemical name (if identified), structure, m/z, retention time and peakhight etc fo reach of the crabs.
It can also be found here: (https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Study&StudyID=ST000922)
 Citation:
 Poulin, R. X., Lavoie, S., Siegel, K., Gaul, D. A., Weissburg, M. J., &amp; Kubanek, J. (2018). 
 Chemical encoding of risk perception and predator detection among estuarine invertebrates. 
 Proceedings of the National Academy of Sciences, 115(4), 662–667. https://doi.org/10.1073/pnas.1713901115 

Folder structure

All code are in Code folder, in future there might be folders as: .ignore (#contains files users won't firectly use)
.figures(of generated figures), etc.
IT is recommended to run the code file X_Y_pset4.py in Colab since it is generated there. Use default Python 3 environment. 
Need to install pandas, numpy, matplotlit.


Figure

This is what the figure looks like after run code on Colab.
