# SIIM-ISIC Melanoma Classification
This repository contains scripts for the Kaggle competition for SIIM-ISIC Melanoma Classification[https://www.kaggle.com/c/siim-isic-melanoma-classification/overview]. The model is required to identify melanoma in images of skin lesions. In particular, images within the same patient will be classified as likely to represent a melanoma or not. 

## Data
Bothe train and test data for the competition can be directly downloaded from the competition page or via Kaggle command line API, which can be installed using pip. 

## Baselinr Model
We selected the pretrained ResNet as the baseline model and plan to build a more roboust, accurate, and efficient model from there. Currently, only vision based deep neural networks are considered for the task. However, in the future, other machine learning models as well as other learning methods should be considered to aggregate both the visual features from the images and the contextual futures from the patients.