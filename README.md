# Intestinal Mast Cell scRNAseq
This repository contains analysis scripts for the manuscript "Intestinal mast cell-derived leukotrienes mediate anaphylactic response to ingested antigens" by Bachtel et al, 2025.

This study is led by the Medzhitov lab at Yale University School of Medicine (Department of Immunobiology).

# Usage
Raw fastq files can be downloaded from the GEO Accession (GSE293906). Processing should follow the Methods section of the manuscript. The provided code for the scRNAseq analysis displays all steps taken from data acquisition, through quality control and pre-processing, clustering, subsequent data analysis, and plot generation presented in the manuscript. While presented as a single R script, the script has been broken into sub-sections pertaining to different steps in the above pipeline. Main Figures, Supplementary Figures, and Supplementary Tables originating from each sub-section are labelled as such to aid in reproducibility. For one figure (Figure 3a) presented in the manuscript, data from Tauber et al 2024 was re-plotted (https://doi.org/10.5061/dryad.np5hqbzzz). The details of how this plot was generated is found in the script for the scRNAseq analysis as well. 

Bulk RNAseq analyses performed and code to generate the plots presented are provided in the Bulk Seq folder. 

# Correspondance
Please refer to the manuscript for correspondance details: ruslan.medzhitov@yale.edu 
