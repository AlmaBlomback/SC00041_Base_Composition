
## Purpose
The purpose of this script, `base_composition.R`, is to count the bases in a fasta dataset and produce a bar chart of the results.  

## Instructions for Running Code

### Clone the repository
To use the repository, first clone it using:
```bash
git clone https://github.com/AlmaBlomback/SC00041_Base_Composition.git
```
### Install dependencies
To use the code the following R packages are required: BiocManager, BioStrings and ggplot2.

Create an environment using `environment.yml` by:
```bash
conda env create -f environment.yml
```
#### Activate the environment
```bash
conda activate base-composition
```
### Run the script
```bash
Rscript base_composition.R
```
## What output to expect
Th output of the script is a figure that is saved in the same folder as the script called base\_plot.png
