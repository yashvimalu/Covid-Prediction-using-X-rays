# Covid-Prediction-using-X-rays
Implemented deep learning project using Tensorflow which could predict whether a person is  suffering from Covid-19 by providing his/her chest X-rays. 

## About the code
We made 2 models
1.	Using MobileNet (Using Transfer learning) 
	-MobileNet is a CNN architecture model for Image Classification and Mobile Vision.There are other models 
        as well but what makes MobileNet special that it very less computation power to run or apply transfer 
	learning to.
        -With MobileNet, the accuracy (0.9595) showed overfitting and the loss was also very high 0.5037.
	So,then we developed another model 

2.	Simple binary classification model using Convolutional Neural Network 
	consisting of Conv2D and MaxPolling layers.
	-Using this, we got an accuracy of 0.9324 and loss of 0.1613.

## About the dataset

We found a dataset on kaggle consisting of 94 images (74 in training and 20 in testing in each category )
in jpg forms divided in 2 categories Normal and Pneumonia in both training and testing.

LINK - https://www.kaggle.com/khoongweihao/covid19-xray-dataset-train-test-sets
