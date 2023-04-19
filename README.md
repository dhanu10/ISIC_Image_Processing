# Project Name

Predicting House Prices using historical data by applying Linear Regression techniques.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Analysis of ISIC Images:

This repository contains an analysis of the images from the International Skin Imaging Collaboration (ISIC) dataset. The dataset contains images of skin lesions, with the goal of improving the accuracy and reliability of melanoma diagnosis.
Objective is to enhance learning of CNN.

Problem Statement:
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Dataset:

The ISIC dataset consists of over 2357 images of skin lesions, categorized into several different classes such as melanoma, nevus, and seborrheic keratosis. 
The dataset was prepared using Keras ImageDataGenerator, and various augmentation strategies were applied to increase the size and diversity of the dataset.

Augmentation Strategies:

Several augmentation strategies were applied to the images in the dataset, including rotation, flipping, and zooming. 
These strategies were applied to the images using the ImageDataGenerator as well as Augmentor library in Python. 
By applying these strategies, the size and diversity of the dataset were increased, which can help improve the accuracy of the machine learning model.

Class Imbalance:

The ISIC dataset suffers from class imbalance, with some classes having significantly fewer images than others.
To address this issue, the Augmentor library was used to balance the classes by oversampling the minority classes. This helped ensure that the machine learning model would not be biased towards the majority classes.
Also method of using different weights for classes was used to see if it can impact training positively.


This assignment helps reenforce some of the concepts abouce image processing, CNN modeling, data agumentation and handing class imbalances.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
In this analysis, we prepared and augmented the ISIC dataset using Keras and the Augmentor library. We also addressed the issue of class imbalance by oversampling the minority classes. 
By applying these techniques, we created a more diverse and balanced dataset that can be used to train a more accurate and reliable machine learning model for skin lesion classification.
While Dropout layer appears important, validation loss and accuracy didn't improve much beyond what was observed in base model without agumentation and balancing of classes.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python : 3.8
- Pandas Version : 1.5.0
- Numpy  Version : 1.23.4
- Seaborn Version : 0.12.0
- Matplotlib Version : 3.6.2
- Tensorflow / keras : 
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Use of this dataset in publications is from following publication:
International Skin Imaging Collaboration (ISIC) dataset



=========================================
Contact
=========================================
	
For further information about this dataset please contact - International Skin Imaging Collaboration (ISIC) 


## Contact
Created by [@dhanu10] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
