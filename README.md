
## Purpose
This script, `base_composition.R`, was written to count the bases in a FASTA dataset and produce a bar chart of the results.  

## Instructions for Running Code

### Clone the repository
To use the repository, first clone it using:
```bash
git clone https://github.com/AlmaBlomback/SC00041_Base_Composition.git
```
### Install dependencies
To use the code, the following R packages are required: BiocManager, BioStrings and ggplot2.

Create and activate an environment using `environment.yml` by:
```bash
conda env create -f environment.yml
```
```bash
conda activate base-composition
```
### Run the script
Run the script using `Rscript` and specify the path to the FASTA dataset to be analyzed. The example data is placed in a data folder within the current directory, but any path can be used. 
```bash
Rscript base_composition.R ./data/fasta.fa
```
## What output to expect
When the running the script, an output folder is created in the current directory. The resulting bar chart is saved in this folder as `base_plot<_date_time_>.png`.

## Authors
For any questions or suggestions, please open an issue in this repository or contact one of the authors: 

Alma Blombäck (<alma.blomback@gu.se>), Felix Falk (<felix.falk@ki.se>), Jacob Holmqvist (<jacob.holmqvist@gu.se>)
