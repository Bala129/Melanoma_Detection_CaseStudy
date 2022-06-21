# Melanoma Skin Cancer Detection Case Study
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Overview
In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.
 - Problem Statement
 To build a CNN based model which can accurately detect melanoma. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
 - Dataset
 The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

## Conclusions
- CNN Model Used
![CNN image](https://github.com/Bala129/Melanoma_Detection_CaseStudy/blob/main/CNN%20Model.png)


- Conclusions
1. CNN Model 1 - From the Training and Validation Accuracy graph it is clear that the model could potentially be overfitting and there is a significant difference between the validation and training dataset.
2. CNN Model 2 - One with Data Augmentation - With Data Augmentation we have been able to reduce the overfitting concept - but however this has significantly affected the accuracy. The validation accuracy has also shown poor performance.
3. CNN Model 3 - One with additional training data set - The training accuracy has reduced indicating a reduction in overfitting. Additionally the accuracy difference between the validation and training accuracy has reduced.



## Technologies Used
- tensorflow
- pandas
- numpy
- matplotlib
- seaborn
- os
- glob


## Contact
Created by [@Bala129] - feel free to contact me!
