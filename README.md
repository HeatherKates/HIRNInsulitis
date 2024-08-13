# scRNAseq of HuBMAP pancreas

This repository contains scripts and files related to the processing and analysis of nCounter protein expression data generated for GeoMX DSP ROIs from inflamed and non-inflamed KO and HE Mus musculus islets.

## Overview

The code provided here is fully reproducible. All required input files are included.

## Directory Structure

- **scripts/**: Contains the Rmd code necessary to reproduce the analysis (QC, normalization, visualizations)
- **results/**: Directory for storing normalized nCounter data and figures
**GeoMX_nCounter.HKnormalized.bgRemoved.xlsx**: Multi-sheet excel with normalized counts with probes below background threshold removed, sample metadata, and feature metadata
**GeoMX_nCounter.HKnormalized.xlsx**: Multi-sheet excel with normalized counts with probes below background threshold included, sample metadata, and $
**PCA_plot.png**: PCA plot of ROIs labeled by islet inflammation and KO vs HET genotype.	
**heatmap_high_res.png**: Heatmap of QC filtered proteins annotated by islet inflammation and KO vs HET genotype. Samples (in columns) are clustered by expression profile.

- **data/**: Directory with nCounter count and sample data exported from the GeoMX DSP Initial Dataset 

## Reproducibility

To ensure full reproducibility, follow the steps below:

1. **Run Scripts**: Use the script provided in the `scripts` directory to process the data and generate results.

## Contact

For questions, please contact:

Heather Kates  
Email: [hkates@ufl.edu](mailto:hkates@ufl.edu)

## License

None

