# HCA_Previewdata
stores the preview data and initial analysis script, data was processed by scPipe.

data was downloaded from [HCA data portal](https://preview.data.humancellatlas.org/)

## Metadata

metadata is stored in [HCA data portal](https://preview.data.humancellatlas.org/) and can be downloaded.

## Count files for R

You can find SingleCellExperiment object for the dataset, either the raw data (`ischaemic_sensitivity_raw.RData`) or processed data (`ischaemic_sensitivity_QC_norm.RData`) after quality control and normalization in `rdata` folder

## data exploration analysis

Rmd document can be found in `script` folder.


## CSV and MTX files

You can find gene count matrix in `data/<dataset_name>/gene_count.csv.zip`. Quality control metrics generated by scPipe during data preprocessing can be found in `data/<dataset_name>/stat`