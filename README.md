# LAND USE AND LAND COVER CLASSIFICATION WITH SENTINEL 2
# Objective
The goal of this project is to determine an accurate and efficient system for classifying satellite images into different land use and land cover classes using different deep learning models. 
# Dataset
The Sentinel-2 satellite images are openly and freely accessible provided in the Earth observation program Copernicus.
Sentinel-2 (S2) is a wide-swath, high-resolution, multispectral imaging mission with a global 5-day revisit frequency. The S2 Multispectral Instrument (MSI) samples 13 spectral bands: visible and NIR at 10 meters, red edge and SWIR at 20 meters, and atmospheric bands at 60 meters spatial resolution. It provides data suitable for assessing state and change of vegetation, soil, and water cover.
# Imlementation
1. DATA ACQUISITION:

      The sentinel-2 dataset is extracted from EuroSat.
      
2. PRE-PROCESSING:

      Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model.
      
3. CREATING THE TRAINING DATASET:

      The dataset is divided into:
      
        7,35,22,331 bytes (111.4 MB on disk) for 21,613 items -> training dataset
        1,83,38,421 bytes (27.7 MB on disk) for 5,413 items -> test dataset
        
 4. FEATURE EXTRACTION AND CLASSIFICATION:
 
       3 Deep Learning Models like RESNET50,VGG16 and VGG19 is used to classify the Sentinel-2 dataset and then the accuracy is calculated.
       
 5. RESULT:
 
        After Implementation, it is observed that:
        RESNET50 gives an accuracy 63%
        VGG 16 gives an accuracy 95%
        VGG 19 gives an accuracy 76%
      Hence, according to this VGG16 gives the best accuracy.

   

