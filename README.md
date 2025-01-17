# Neural-Retina-Atlas

This repository contains the scripts used for the paper 'A proteogenomic atlas of the human neural retina'(link)

## Data
Raw PacBio Iso-Seq data are available at the  European Genome-phenome Archive (EGA) under accession number EGAD50000000101. The mass-spectromety proteomics data have been deposited to the ProteomeXchange Consortium via the PRIDE​​ partner repository with the dataset identifier PXD045187. Intermediate files generated during the analysis and reference files can be downloaded from Zenodo:
* reference data: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10371435.svg)](https://doi.org/10.5281/zenodo.10371435)
* intermediate analysis files: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10371395.svg)](https://doi.org/10.5281/zenodo.10371395)


The processed data is available as UCSC genome browser track (https://genome-euro.ucsc.edu/s/tabeariepe/retina_atlas).

## Scripts

- [Data](data) can be used to store the downloaded data from Zenodo to rerun the scripts
- [Figures and Tables](figures_and_tables) contains scripts used to create the figures and tables
- [Proteomics](proteomics) contains all scripts used for the proteogenomic analysis
- [Transcriptomics](transcriptomics) contains all scripts for the Iso-Seq analysis
- [Retina specific exons](retina_specific_exons) describes how we looked for previous identified retina-specific exons in our PacBio dataset
- [Scripts](scripts) contains small scripts and functions used for the analysis

