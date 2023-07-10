Hippomap contains a set of tools for mapping data to the folded and unfolded hippocampus as generated by [HippUnfold](https://github.com/khanlab/hippunfold) and using the [HippUnfold_toolbox](https://github.com/jordandekraker/hippunfold_toolbox). Here, we map:
- ex-vivo histology (various stains and contrasts)
- resting state fMRI connectivity (rsfMRI FC)
- structural MRI (morphometry and various modality intensities)
- intracranial EEG (iEEG) recodings

Tutorials are shown in `notebooks/`, but it is also recommended that you take a look at the HippUnfold_toolbox tutorials for things like learning how to load nifti/gifti data and use some of the plotting functions. This project also relies heavily on neuroimaging toolboxes [wb_command](https://www.humanconnectome.org/software/workbench-command/) and [ANTs](http://stnava.github.io/ANTs/). 

`sourcedata/` and `hippunfold/` are currently unavailable, but will eventually host the original data (in BIDS format) and HippUnfold outputs for all subjects. 
