# DSC180-Functional-Connectivity-Project

## Project Structure:

`main.ipynb` is the combination of all of our analysis and exploration on dynamic functional connectivity.



## How to get the data?

For this project, we use the resting fMRI data from the Human Connectome Project (HCP) from this [paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC3724347/) and the data description can be found [here](https://www.humanconnectome.org/storage/app/media/documentation/s1200/HCP1200-DenseConnectome+PTN+Appendix-July2017.pdf). 

In order to download the data you will need to make an account [here](https://db.humanconnectome.org/app/template/Login.vm;jsessionid=67A8B8766DEEA4CF0597C483C9203BE2). Then you can download timeseries data for each subject. Navigate to section titled *WU-Minn HCP Data - 1200 Subjects* and click *open dataset*. Find section titles *HCP1200 Parcellation+Timeseries+Netmats (PTN)* and download the 1003 subject data. Note: you may need to download IBM Aspera Launcher from [here](https://www.ibm.com/products/aspera/downloads#cds) in order to download the data. 

Once you have the data download, you will be able to find the timeseries data in the folder titled `node_timeseries` and for our analysis we are using the data in the `3T_HCP1200_MSMAll_d100_ts2` folder which is stored originally as `NodeTimeseries_3T_HCP1200_MSMAll_ICAd200_ts2.tar.gz`. We are also using the file in the following path `HCP_PTN1200/groupICA/groupICA_3T_HCP1200_MSMAll_d100.ica/melodic_IC_sum.nii.gz` to plot our findings on the atlas of the brain.


## Which Packages are necessary?
In order to run our notebook you would need to have the following packages installed:
* jupyter notebook
* ipykernel
* numpy
* matplotlib.pyplot
* nilearn
* nibabel
* sklearn
* atlasreader



<!-- Task for next week:
* try analysis on different d resolutions
* try combining the subjects by averaging over the time series
* try combingng the subjects by averaging over the datapoints across subjects??? (Not sure abt this one)
* read the research paper

Q1 project:
* map brain connectivity -->
