# Brain_tumour_segmentation

This will be my progress traccker of what i have done in the project:
- The data contains brain MR images together with manual FLAIR abnormality segmentation masks.
The images were obtained from The Cancer Imaging Archive (TCIA).
They correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available.
- More information of the data can be found here:https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation/data.
- The first thing is to install modules, i decided to use my machine to work on the above dataset. the only change was pip installing segmentation-models-pytorch,since it is a very large module.
- Next is getting the csv files and the .tif files containing mri images.(very large too)
- Next i took care of the missing values ,never used knn imputer before so i decided to use it anyway since most of the data plots were normaly distributed.
