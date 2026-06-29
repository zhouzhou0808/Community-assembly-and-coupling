Project Overview：    
    This repository contains the R scripts used for the analyses presented in our manuscript, which is currently under peer review. The workflow focuses on bacterial community assembly, cross-habitat microbial interactions, and the ecological effects of wintering waterbirds in river-connected lake wetlands.

Data Availability：    
    To protect unpublished data associated with the manuscript under review, raw metagenomic sequencing data and environmental metadata are not included in this repository.    
    To run the scripts, users should prepare input files with the following structure:    
    Species abundance matrix: rows represent taxa (e.g., phylum or genus) and columns represent samples.    
    Environmental data table: sample IDs together with physicochemical variables (e.g., nutrients, chlorophyll a, temperature and other environmental indicators).    
    Sample metadata: sample grouping information, including wintering stage (early vs. late wintering period) and habitat type (water vs. sediment).    

Recommended Analysis Workflow：    
    1.Preprocess sequencing data and calculate relative abundances.    
    2.Perform community profiling using Other analysis.R (community composition and differential analyses).    
    3.Perform bacterial community structure ordination using PCA.R.    
    4.Characterize community assembly using NCM.R (Sloan neutral community model).    
    5.Construct microbial association networks using WGCNA.R and summarize module characteristics using Number of modules.R.    
    6.Evaluate direct and indirect environmental effects using PLS-PM.R.    

Important Notes：    
    Manuscript status: The associated manuscript is currently under peer review.    
    Code customization: File paths, sample names, grouping variables and filtering thresholds should be modified according to the user's dataset before running the scripts.    
    Outputs: The scripts generate publication-quality figures, statistical summaries and model outputs that can be used for manuscript figures and supplementary materials.    
    Support: For questions regarding the analytical workflow or code implementation, please contact the corresponding author.    

Citation：    
    If this repository contributes to your research, please cite the corresponding publication once it becomes available.
