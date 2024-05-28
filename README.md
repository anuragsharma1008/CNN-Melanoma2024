# CNN-Melanoma2024
About use of CNN model to Evaluate images and alert dermatologists about the presence of melanoma (a type of skin Cancer)
# Project Name
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a CNN based model which can accurately detect melanoma
- Application of CNN Techniques
- By this project, we can identify the nature of disease only by seeing the image
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
1. As the training accuracy increases linearly over time, where as the validation accuracy increases in training process.
2. As the training loss decreases with epochs the validation loss also decreases.
3. The plots show that gap between training accuracy and validation accuracy have decreased significantly from previous model, and it has achieved around 75% accuracy on the validation set.
4. The difference in accuracy between training and validation accuracy is very less
5. The Model can be further improved by tuning the hyperparameters
6. If the model overfits (high training accuracy but low validation accuracy), consider applying regularization techniques such as Dropout, L2 regularization, or increasing the amount of training data. If the model underfits (low training and validation accuracy), consider using a more complex model or fine-tuning hyperparameters.
7. A CNN model can be very effective in detecting melanoma from images of skin lesions. By carefully preparing the data, defining an appropriate model architecture, and applying necessary augmentation and regularization techniques, you can build a model that generalizes well to unseen data. This can assist in early detection of melanoma, potentially saving lives through timely medical intervention.


## Technologies Used
1. pathlib
2. tensorflow
3. matplotlib & pyplot
4. numpy & pandas 
5. keras
6. layers
7. Sequential from tensorflow.keras.models 

## Acknowledgements

- This project was done to demonstrate the Power of CNN in medical field.



## Contact
Created by anuragsharma1008 - feel free to contact me!
