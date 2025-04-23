---
layout: home
title: Home
nav_order: 1
---

# Documentation 
Documentation of our group's bioinformatics pipeline. 
- The Github folder containing the pipeline, this documentation, example cases, and the tutorial is accessible [here](https://github.com/luquelab/Bioinformatics_Too_Indecisive).
- The pipeline is accessible [here](https://github.com/luquelab/Bioinformatics_Too_Indecisive/blob/main/notebooks/Group_2_(Too_indecisive)_.ipynb).
- The repository contains example data. The folder is accessible [here](https://github.com/luquelab/Bioinformatics_Too_Indecisive/tree/main/example).

## Overview of the tool and its purpose
This is a reproduceable bioinformatics pipeline which can take as input a list of DNA sequences and perform an in-depth sequence analysis. It is designed to require minimal setup beyond placing the input data in the correct folder.

The pipeline can: 
- investigate the sequence properties
- predict their functions
- predict their organisms of origin
- explore their evolutionary relationships

## Installation instructions
The entire pipeline is downloadable as a Jupyter file (.ipynb). Go to the /notebooks folder on our Github page and download main_pipeline.ipynb. You can open it either on Google Colab or on a IDE of your choice such as Visual Studio Code, provided it can open Jupyter files. Make sure your sequences are saved in the fasta format in a file which you must name sequences.fna and import that file in the /data folder in the same folder where the pipeline is located. Run the pipeline. 

## Usage guide with examples
See the example folder on Github. Alternatively, you may refer to our tutorial for further guidance. 

## Technical details about the implementation
The pipeline is written entirely in Python and uses standard scientific and bioinformatic libraries such as:
- Biopython for handling FASTA files, sequence analysis, and accessing biological databases
- scikit-learn and NumPy for statistical analysis and machine learning-based function prediction
- matplotlib and seaborn for data visualization
- BLAST+ (via command-line calls) for identifying homologous sequences and predicting organisms of origin
- Clustal Omega for multiple sequence alignment and phylogenetic analysis

## Contribution guidelines for future development
We welcome contributions from the community to improve and expand the functionality of this pipeline. Feel free to contribute by forking the Github repository and creating a new branch with your desrired modifications. Please make sure to include example cases and proper documentation before submitting a pull request.
