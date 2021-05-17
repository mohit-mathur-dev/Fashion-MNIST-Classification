# Fashion-MNIST-Classification
This repo contains the famous Fashion MNIST Image Classification task which gives approx 94% Test Accuracy.

## Datasets 
Dataset is already available inside the keras library. You can load the data using `keras.datasets.fashion_mnist.load_data()`. Read more about the Datasets [here](https://www.kaggle.com/zalando-research/fashionmnist)

### Data Preprocessing
As Keras provides us the almost processed Fashion MNIST data, we have just scaled down the images and bring down the pixel range in between 0 to 1 by dividing the each image array by 255. and add 1 more axis (channel axis i.e. 1).

## Model Architecture
We have used several Conv2D, Max Pooling, Batch Normalization, Dropout and Dense layers. Refer the following model architecture:  

![](model-architecture.png)

## Results and Evaluation
Classfiction Report for this project is as follows: 

![](classification-report.PNG)


We have got 93.81% Testing Accuracy and 93.81% F1-score.
