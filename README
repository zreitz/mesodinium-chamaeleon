# Supplemental code for "Integration and regulation of stolen organelles in Mesodinium chamaeleon"

## Abbreviations:
- MC = *M. chamaeleon* macronucleus
- KN = *S. major* kleptokaryon
- SM = Freeliving *S. major* nucleus


## Contents
Each R notebook (`.rmd`) has been knitted into an HTML document and includes `sessionInfo()`.
- `physiology/`
    - `input/FIReData.csv`: Photophysiology data for the time course experiment
    - `input/MC_starv_export.csv`: Physiology data for the time course experiment
    - `StarvationExpt.Rmd`: Processing and analysis of physiology data and correlation with transcriptomic data (from `2_proportions/`)
    - `physiology-plots.rmd`: Additional plotting of physiology data

- `0_databases/`
    - `kegg_parsing.rmd`: Pre-processing to parse the KEGG BRITE hierarchy
- `1_counts_processing/`
    - `input/`: Per-KO counts (`[org]_quantReads/`) and associated metadata for MC and KN (`meta.txt`) and SM (`sm_metadata.csv`)
    - `data-processing.rmd`: Processing and filtering for MC and KN
    - `data-processing-freeliving.rmd`: Processing for SM
    - `co-processing-kn-vs-freeliving.rmd`: Processing for KN vs SM comparisons
- `2_proportions/`
    - `proportions-KEGG.rmd`: Proportions of mapped reads in each KEGG subcategory for MC and KN
    - `vs-freeliving.rmd`: Proportions of mapped reads in each KEGG subcategory for KN vs SM
- `3_deseq-gsea/`
    - `a_deseq.rmd`: Differential expression analysis for MC and KN
    - `b_upset.rmd`: Statistics for the numbers of up- and down-regulated genes 
    - `c_gsea.rmd`: Gene Set Enrichment Analysis (GSEA) for MC and KN
- `4_specific-pathways`
    - `nitrogen.rmd`: Expression of nitrogen acquisition genes in MC
