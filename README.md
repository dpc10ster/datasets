# datasets
Datasets used in my collaborations

This repository contains all datasets (that I could retrieve, some are unfortunately lost) used in my collaborations. 
* `xlsx` files are in JAFROC format (as desribed in my package `RJafroc`)
* `lrc` (text) files are in MRMC lrc format (see publications by Iowa ROC research group)
* Use RJafroc::DfReadDataFile() to read these files into a `dataset` object
* DfReadDataFile(
  fileName,
  format = "JAFROC",
  newExcelFileFormat = FALSE,
  delimiter = ",",
  sequentialNames = FALSE
)
