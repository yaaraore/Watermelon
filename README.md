# Watermelon
Data and code related to the paper:cycling cancer persister cells arise from lineages with distinct programs (https://www.nature.com/articles/s41586-021-03796-6)
For any addiotnal code request or questions please email me (yoren@broadinstitute.org). 

This project contains two directories code and data.

The code directory contains:
  1) R script 
  2) R script 
 
The data directory contains
  1)V3 Seurat R objects pc9_time_course.rds- transcriptome of PC9-watermelon cell lines across osimertinib treatment. Lineage barcodes are found in the metadata       file associated with the Seurat objects
  
  2)V3 Seurat R objects pooled_persisters.rds-transcriptome of multiple watermelon cell lines at day 0 and 10 of drug treatment. Cell line indenty is found in the     metadata file associated with the Seurat objects
  Both objects can be loaded using the readRDS R function if the Seurat libraray is loaded

