# chrom-track

*TODO:* 

*1. Make user parameter input easier*

*2. Add choice of passing multiple directories for different conditions (eg transcribing or not) and comparing them*


My code for chromatin tracking analyses.

Download this folder or just the yml file and navigate in the miniforge terminal to the directory. Then run:

```
mamba env create -f environment.yml
mamba activate chrom-track
jupyter notebook
```

This will install the dependencies, activate the environment, and open up jupyter notebook. 
Now you can open chromtrack.ipynb, change the directory path to your files, and run. 

The example dataset is in 'telomeres' folder and contains ThunderStorm localization csvs of dCas9-labeled telomeres in U2OS cells, imaged at 20 Hz.

The outputs are: (1) the recovered trajectories, (2) the iMSDs, and (3) the MSD fits (D* and alpha), and various plots.

compare_parameters.ipynb can be used to compare two datasets (the example data in the //compare// folder is just a copy of the same dataset, so there will be no difference)


