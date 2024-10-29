# Melanoma-CNN-Prediction


## General Information
- In this assignment, you will create a multiclass classification model by building a custom convolutional neural network using TensorFlow.
- In this project, we aim to solve the problem of accurately classifying skin lesions as malignant (melanoma) or benign using a Convolutional Neural Network (CNN). By training the CNN on a labeled dataset of skin images, the model will learn to detect patterns that differentiate melanoma from benign conditions, assisting in early and reliable skin cancer diagnosis. This approach can support dermatologists in identifying melanoma cases more efficiently and potentially improving patient outcomes
- The dataset consists of 2,357 images of malignant and benign oncological conditions, obtained from the International Skin Imaging Collaboration (ISIC). Each category was organized according to ISIC’s classification, with an equal number of images in each subset.
- The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion
 
## Conclusions

- The model without Batch Normalization showcases high accuracies in terms of both training(80%) and validation(81%).

- The rebalancing has reduced the effects of overfitting. It has also slightly increased the accuracy.

- While the model with Batch normalization reduced the effects of overfitting, its accuracies were low (around 60-64%) for both training and validation.

- The inclusion of batch normalization is considered to be not effective in increasing the efficiency.

- The final model without batch normalization is effective in learning the general behavior and underlying information of the dataset

## Technologies Used
- Python - version 3.10.12
- Matplotlib - version 3.7.1
- Numpy - version 1.26.4
- Pandas - version 2.2.2
- Seaborn - version 0.13.2
- Tensorflow - version 2.17.0


## Acknowledgements
- Upgrad Tutorials on the topic - CNN
- [Augmentor]https://augmentor.readthedocs.io/en/master/userguide/examples.html

