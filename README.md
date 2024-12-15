# Programming-Assignment
## Programming Home Assignment:fMRI Data Visualisation - Social interaction
This project visualises fMRI data using python and data from Neurosynth. This analysis focuses on social interaction as its topic, and overlays functional data over an anatomical scan as well as creates a histogram of the data. This assignment is part of the Programming for Psychologists course.

Gwendolyn Bossuyt
13.12.2024

Neurosynth link to the files used: https://neurosynth.org/analyses/terms/social%20interaction/

## Table of contents:
1. Data: 
   - Functional data: A uniformity test
   - Anatomical data: A structural MRI scan

2. Notebook:
   - `Assignment.ipynb`: A Jupyter notebook containing all the code and outputs of the project, as well as Markdown cells explaining what was done.

3. Outputs:
   - Functional MRI visualisation: Functional data overlayed over the anatomical MRI scan
   - Histogram: A histogram plotting the intensity value distribution of the fMRI data

4. Pull request:
   - Evidence of a pull request in the form of a screenshot of my submitted comments
  
## Python packages used
   - `os` and `glob` for automatic file localisation
   - `matplotlib` for data visualisation and plotting figures
   - `nilearn` for neuroimaging visualisation
   - `nibabel` for loading and extracting file data

## Instructions
1. Go to Neurosynth.org and download the data
   - Choose a topic -- I chose social interaction
   - Under 'Layers', download the following files:
       - `uniformity test`: the functional data file
       - `anatomical`: the anatomical scan
2. Organise files
   - Place the downloaded files (will be `nii.gz` format) into the same folder as the Jupyter notebook to ensure the code can locate the sata files
  
3. Run the notebook
   - If you wish to choose a different topic, make sure that you alter the `topic_name` and `functional_file_name` to ensure the figures plot the correct data and are titled correctly. If you do not alter these, the code is set to run the analysis for social interaction.
