# Brain_tumour_segmentation

This will be my progress traccker of what i have done in the project:
- The data contains brain MR images together with manual FLAIR abnormality segmentation masks.
The images were obtained from The Cancer Imaging Archive (TCIA).
They correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available.
- More information of the data can be found here:https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation/data.
- The first thing was to install modules, I decided to use my machine to work on the above modelling of the mri segmentation modelling using pytorch. The only challenge was when pip installing segmentation-models-pytorch,it is a very large module.
- Next was getting the csv files and the .tif files containing mri images.(very large too)
- Next i took care of the missing values ,never used knn imputer before so i decided to use it anyway since most of the data plots were normaly distributed(from the plotted histograms).
