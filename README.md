## Project Name: Melanoma Detection Assignment

In this assignment, I have built a multiclass classification model using a custom convolutional neural network in TensorFlow. 

## Table of Contents:

Problem statement and General Info

Libraries Used

Conclusions

## Problem statement and General Info: 

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Libraries Used:

pathlib

tensorflow as tf

matplotlib.pyplot as plt

numpy as np

pandas as pd

PIL

## Conclusion:

Overfitting has solved by using Image augmentation

Augmentor with samples (1000)

Underfitting and overfitting has been solved

Training and Validation accuracy are close - 0.87

Rectifying the class imbalance got rid of underfitting
