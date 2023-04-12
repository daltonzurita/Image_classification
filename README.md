# Image Classification: Sedans, SUVs, and Trucks

This project focuses on classifying images of vehicles into three categories: sedans, SUVs, and trucks. A Convolutional Neural Network (CNN) is used for image classification, which is an important task in computer vision and has numerous applications, such as autonomous driving and vehicle recognition systems.

## Dataset

The dataset used in this project contains images of sedans, SUVs, and trucks, along with their corresponding labels. 

## Model

In this project, a Convolutional Neural Network (CNN) is used for image classification. The CNN architecture consists of the following components:

- Data augmentation techniques, including horizontal flipping, rotation, and zooming
- Rescaling layer to normalize pixel values
- Three convolutional layers with ReLU activation and same padding, followed by max-pooling layers
- Dropout layer to reduce overfitting
- Flatten layer to convert the feature maps into a 1D tensor
- Dense layer with 128 neurons and ReLU activation
- Output dense layer with a number of neurons equal to the number of classes

## Evaluation

The performance of the CNN is evaluated using accuracy as the main metric. The higher the accuracy, the better the model is at correctly classifying images of sedans, SUVs, and trucks.

## Results

The trained CNN achieved an accuracy of 91% on the test set, demonstrating its ability to effectively classify images of sedans, SUVs, and trucks.
