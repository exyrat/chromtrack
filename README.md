# chrom-track
My code for chromatin tracking analyses.

Download this folder or just the yml file and navigate in the conda terminal to the directory. Then run:

conda env create -f environment.yml
conda activate chrom-track
jupyter notebook

This will install the dependencies, activate the environment, and open up jupyter notebook. 
Now you can open chromtrack.ipynb, change the directory path to your files, and run. 

The example dataset is in 'uf_roi' folder and contains 19x19 ROI movies around a labeled genomic locus.

The output is a plot of: (1) the recovered trajectory, (2) the MSD, and (3) the MSD fit for each movie/locus, and at the end boxplots of the estimated parameters for all movies/loci.
