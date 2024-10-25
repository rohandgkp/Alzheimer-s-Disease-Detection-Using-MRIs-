# Alzheimer-s-Disease-Detection-Using-MRIs-
The MRI image dataset consists of 4 classes - Mild Demented, Very Mild Demented, Moderate Demented, and Non-demented.
The dataset was divided into 2 parts for training (80%) and testing (20%).
This project involves 2 phases- Before Augmentation and After Augmentation.
In the first phase, pre-existing models such as ResNet50, InceptionV3, AlexNet, and VGG19 were employed and in addition to that a custom CNN model was built.
The training was done over 100 epochs, with an early stopping of 10 epochs.
In the second phase, data augmentation was performed - RandomFlip, RandomRotation, RandomZoom.
A dropout layer was added to the models and trained over 100 epochs.
The custom CNN model outperformed the other 4 models after augmentation by achieving a testing accuracy and loss of 99.79% and 0.0205. 
