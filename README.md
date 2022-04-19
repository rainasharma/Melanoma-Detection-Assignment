# Melanoma-Detection-Assignment

# Project Name
> Melanoma Detection.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project builds a multiclass classification model using a custom convolutional neural network in tensorflow.

<b>Problem statement</b>: <br>To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.<br><br>
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. <br>The data set contains the following diseases:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion


<b>Project Pipeline</b></br>
* Data Reading/Data Understanding </br>
* Dataset Creation
* Dataset visualisation 
* Model Building & training 

After building model, we observed whether there is model overfit or underfit
Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data.
Create a CNN model, which can accurately detect 9 classes present in the dataset. 

This models examines following question
* Examine the current class distribution in the training dataset
* Which class has the least number of samples?
* Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances:
* Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:
* Write your findings after the model fit, see if the issues are resolved or not?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1 : The model is overfitting because the accuracy on train dataset is quite high 0.927 while on the validation set is quite low i.e. 0.53.
- Model 2 : There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation
- Model 3 : Accuracy on training data has increased by using Augmentor library

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow
- keras
- numpy, pandas

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on [this tutorial](https://tensorflow.google.cn/tutorials/images/classification#visualize_training_results).


## Contact
Created by [@rainasharma] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
