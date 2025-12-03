# preprocessing_raw_dbgap
Code for preprocessing raw data with dbgap attributes 
The sample dataset for this iteration is
Eric A. Collison 2014
Fresh-frozen lung adenocarcinoma specimens.
Method 1 to download files:
  - go to https://portal.gdc.cancer.gov/
  - look up TCGA-LUAD, select and create a cohort and name it.
  - go to repository, select open, transciptome profiling, gene expression quantification, and star-counts.
  - download.
Filter	                        Purpose in pipeline
Open	                          lets you analyze without access barriers
Transcriptome Profiling	        picks the RNA expression biology layer
Gene Expression Quantification	gives you numerical expression columns
STAR – Counts	                  enforces a consistent counting workflow so the matrix is valid.
Method 2 to download files:
rawfiles
