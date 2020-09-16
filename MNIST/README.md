# Handwritten Digit Classification with TensorFlow

## Description
	The MNIST dataset contains 70,000 28x28 pixel images of handwritten numbers. This is one of the most popular datasets for machine 
	learning image processing. The goal of this project is to train a model on the training images and test the model accuracy with 
	the test images. Each images is an array of 784 values between 0 and 1. The value represents a gray scale where 0 is black and 
	1 is white.
	
	The first method I will be using is a softmax regression approach. This approach will use the data in one dimension as an array, 
	784 pixels in length. This is a more simple approach but less accurate. Image processing is most useful when we associated 
	pixels near eachother in the image, with eachother.When viewed in one dimension, pixels near eachother will not necessarily be 
	near eachother in the array. Instead, we are determining the impact of each individual pixel on the image, rather than groups 
	of pixels. I use gradient descent to train the model. When testing the model, we take in the pixel data and output a probability 
	between 0 and 1 for each of the 10 possible numbers. The highest probability value is the returned value. This method produced at 
	88.6% accuracy.
	
	In the second model we use a convolutional neural network to process the images. This is the superior method because we can look 
	at the image in two dimensions. This allows us to find edges and other features in the image to help determine the handwritten 
	number. This model also uses a softmax activation function to predict the handwritten numbers. This method has a 98.8% accuracy.
	
## Prerequisites

##### Software
Jupyter, 
Python

##### Packages
TensorFlow, 
MatPlotLib 

## Acknowledgment
This project was inspired by Jose Portilla's TensorFlow course on Udemy