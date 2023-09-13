# Melanoma-Detection
- To develop a model using CNN that can precisely identify melanoma. Melanoma, a potentially lethal type of cancer if not caught early, is responsible for 75% of skin cancer fatalities. A system capable of analyzing images and notifying dermatologists of melanoma presence could significantly decrease the manual work required for diagnosis.


## Table of Contents
- [Melanoma Detection Assignment](#melanoma-detection-assignment)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)


## General Information
- The dataset, sourced from the International Skin Imaging Collaboration (ISIC), comprises 2357 images representing both malignant and benign oncological conditions.
- The images have been organized based on the ISIC classification, ensuring equal distribution among all subsets. However, the images of melanomas and moles are slightly more prevalent.
- The diseases included in this dataset are: 
**Actinic keratosis**  
**Basal cell carcinoma**   
**Dermatofibroma**  
**Melanoma**  
**Nevus**  
**Pigmented benign keratosis**  
**Seborrheic keratosis**  
**Squamous cell carcinoma**  
**Vascular lesion**



## Conclusions
A CNN model was developed to identify melanoma. The initial model, comprising 3 convolutional layers and a dense layer, exhibited overfitting. To counteract this, we incorporated more augmented images. The subsequent model, built similarly but with the augmented images, managed to mitigate overfitting, though its accuracy was subpar. We identified a class imbalance in our dataset. Using the Augmentor library, we balanced the dataset by augmenting images until each class contained 500 images. The visual representation of the class imbalance. Our third model iteration, constructed with the balanced dataset, not only addressed overfitting but also demonstrated commendable accuracy. The graph showcasing the training and validation accuracy.


## Technologies Used
- pathlib - 1.0.1
- tensorflow - 2.13.0
- seaborn - 0.12.2
- matplotlib - 3.7.1
- numpy - 1.23.5
- pandas - 1.5.3
- Augmentor-0.2.12

## Acknowledgements
- This assignment is part of the course Executive PG Programme in Machine Learning and Artificial Intelligence offered by UpGrad.
- The dataset is provided by UpGrad.


## Contact
Created by [@mikenextml]
