# DICOMScanClassification_iMRI

This repository holds the code for the iMRI Symposium poster "Image and Metadata Fusion for Automatic Classification of Prostate MR Series". See the symposium information [here](https://imri2024.org/). 

## Abstract

With the wealth of medical image data, efficient curation is essential. Assigning the sequence type to magnetic resonance images is necessary for scientific studies and artificial intelligence-based tasks. Incomplete or missing metadata prevents effective automation, leading to time-consuming and error-prone processes by clinicians. We propose a deep-learning method for classification of prostate cancer scanning sequences based on a combination of image data and DICOM metadata. We demonstrate superior results compared to metadata or image data alone, and make our code publicly available at https://github.com/deepakri201/DICOMScanClassification_iMRI.

## Code

[DICOMScanClassification_setup_data_exp6C.ipynb](DICOMScanClassification_setup_data_exp6C.ipynb)
This notebook is for querying Imaging Data Commons data, and obtaining the appropriate metadata from the DICOM files. 

[DICOMScanClassification_train_and_test_exp6C.ipynb](DICOMScanClassification_train_and_test_exp6C.ipynb) This notebook is for the training and test data setup, running training/validation for the three models, and for running inference. Figures and tables are also produced in this notebook. 

[DICOMScanClassification_examine_results_exp6C.ipynb](DICOMScanClassification_examine_results_exp6C.ipynb) This notebook is for the training and test data setup, running training/validation for the three models, and for running inference. Figures and tables are also produced in this notebook. 


## Notes

Further details will be added to this page about how to use the code.



Deepa Krishnaswamy (dkrishnaswamy@bwh.harvard.edu), October 2024, Brigham and Women's Hospital
