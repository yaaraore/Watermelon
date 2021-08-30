# Watermelon
Data and code related to the paper:cycling cancer persister cells arise from lineages with distinct programs (https://www.nature.com/articles/s41586-021-03796-6)
For any addiotnal code requests or questions please email me (yoren@broadinstitute.org). 

This project contains two directories Code and Data.

The Code directory contains:

  1)R script 10X_WTA_dialOut.md- this script created a cell-barcode:lineage-barcode directory based on a dial-PCR of watermelon mammalian lines 
  
  2)R script plasmid_pool_barcode_dialOut- this script is used to assess complexity of a watermelon plasmid pool. It is typically used on a dial-PCR of a             bacterial maxi prep
  
The Data directory contains:

  1)V3 Seurat R objects pc9_time_course.rds- transcriptome of PC9-watermelon cell lines across osimertinib treatment. Lineage barcodes are marked in the metadata       file associated with the Seurat objects (dim: 22166 56419)
  
  2)V3 Seurat R objects pooled_persisters.rds-transcriptome of multiple watermelon cell lines at day 0 and 10 of drug treatment. Cell line identity
  is marked in the metadata file associated with the Seurat object.
  
  Both objects can be loaded using the readRDS R function if the Seurat library is loaded (dim: 23168 50735)

