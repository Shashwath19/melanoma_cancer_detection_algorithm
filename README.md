# Project Name
Melanoma Detection Assignment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
 
The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion.

## Conclusions
The goal is to build the CNN model which will detects the type of cancer. The given input data has 9 different classes. Initialy a model has been built using given data & its observed that the accuracy is low & model is Overfitting. Its also oberved that some of the classes of having very less images & some classes have more images. Augmentation method is added to generate more images for each classes & the model is built again using augmented data.




## Technologies Used
- python 3, Keras & TensorFlow


## Contact
Created by [shashwath19@gmail.com] - feel free to contact me!
