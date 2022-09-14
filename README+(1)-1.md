# Melanoma Skin Cancer Detection

## Abstract
There are more than 200 distinct types of cancer.
Melanoma is the most deadly type of skin cancer out of 200.
Clinical screening is the first step in the melanoma diagnosis process, which is then followed by dermoscopic analysis and histological investigation.
Skin cancer with melanoma has a good chance of being cured if it is discovered in its early stages.
Visual inspection of the afflicted region of skin is the initial stage in the diagnosis of melanoma skin cancer.
Dermatologists use a high-speed camera to capture dermatoscopic pictures of skin lesions, which have an accuracy of 65–80% in the diagnosis of melanoma without any extra technical assistance.
The overall accuracy of melanoma diagnosis increased to 75-84% with additional visual assessment by cancer treatment specialists and dermatoscopic pictures


## Problem Statement
The creation of a CNN-based melanoma detection model. If melanoma is not found in its early stages, it can be fatal. 
It is responsible for 75% of skin cancer fatalities. A system that can analyse photos and notify doctors of the existence of melanoma might potentially 
eliminate the need for a lot of manual diagnosis work. 

## Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.

To overcome the issue of class imbalance, used a python package  Augmentor (https://augmentor.readthedocs.io/en/master/) to add more samples across all classes
 so that none of the classes have very few samples.


## Conclusion
Issue with model overfitting is resolved.
The training accuracy and validation accuracy both rise with the final model (model3).
Class rebalancing aids in augmentation and the greatest possible training and validation accuracy.
