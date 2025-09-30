# Methylation_ChromatinAccssibility
Investigating the interplay between DNA methylation and chromatin modifications in cancers, primarily focusing on TCGA BRCA.

### Data sourced from:
- Access to all data from the study is available at: https://xenabrowser.net/datapages/?cohort=GDC%20TCGA%20Breast%20Cancer%20(BRCA)&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443 <br/>

Specific data sets used for this study is available as:
- BRCA Methylation: https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-BRCA.methylation450.tsv.gz (direct download link)
- BRCA ATAC-seq: https://tcgaatacseq.s3.us-east-1.amazonaws.com/download/brca%2Fbrca_peak_Log2Counts_dedup (direct download link)
- LUSC Methylation: https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-LUSC.methylation450.tsv.gz
- LUAD Methylation: https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-LUAD.methylation450.tsv.gz
- LUSC and LUAD ATAC-seq: https://tcgaatacseq.s3.us-east-1.amazonaws.com/download/TCGA_ATAC_peak_Log2Counts_dedup_sample.gz

<br/>
Note that all methylation assays results were taken from Illumina Human Methylation 450k.

## Final Results
The final results were taken from Analysis_Pipeline_v9.Rmd and the PanCan.Rmd, and the data was stored in a secondary directory named 'Data' from where the code is being run.
