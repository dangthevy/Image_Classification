# Image-Classification:
A Deep Learning Project consisting of image classification and gradio interface for recognising and classifying traffic signs.
Here we will be using Convolutional Neural Networks beacuse of their superior performance with image inputs.
## Convolutional Neural Network(CNN)
A Convolutional Neural Network (CNN) is a type of artificial neural network specifically designed for processing structured grid data, such as images and videos. 

<br>
They have three main types of layers, which are:
<br>

1 . Convolutional layer
<br>
2 . Pooling layer
<br>
3 . Fully-connected (FC) layer
<br>

## What are we doing in this project?
In this particular project we will be working upon Image Classification using Convolutional Neural Network(CNN). We are using CNN because of its superior performance with image classification models.

<br>

Here we are classifying three categories of traffic signs namely:
<br>
<br>

[a] No Parking
[b] One Way
[c] Zebra Crossing
<br>

![jpgtopngconverter-com (1)](https://github.com/Parth-Ach2002/Image-Classification/assets/141126437/7ffa33af-f59e-43ef-9154-38fceac209d8) 
![jpgtopngconverter-com](https://github.com/Parth-Ach2002/Image-Classification/assets/141126437/ae32cb74-ec1d-4a3e-9636-0a8b47c414e0) 
![WhatsApp_Image_2023-08-27_at_17](https://github.com/Parth-Ach2002/Image-Classification/assets/141126437/aa215b4b-3007-4291-98d2-3eb8e7cec113)


## How did we collect our data?
Most of our images is collected by us through mobile photography. We went to multiple roads and clicked the photos of our desired traffic signs and aggregated them together in the form of a dataset. 
<br>
Some of our images is also collected through online sources and then we combined every photos to form a perfect dataset of images with the same image type. 
We also went through the street view of google maps and captured the images of traffic signs in the form of screenshot.
<br>

## Procedure
### Importing libraries
The necessary libraries are imported for preprocessing and model creation.
<br>

### Importing data file
Dataset is uploaded for the further use.
<br>

### Preprocessing
Data is rescaled and normalised in order to maintain uniformity. Here uniformity means converting all the images to a fixed size for better performance of model.
<br>
A little bit of data augmentation has also been performed.
<br>

### Model creation 
A Sequential model using Convolutional Neural Network(CNN) is created.
We are using three input layers and three dense layers along with dropout layers.
This model exists within a function with varying range of paramters.
<br>

### Compilation and fitting
 Model compilation is an activity performed after writing the statements in a model and before training starts. It checks for format errors, and defines the loss function, the optimizer or learning rate, and the metrics. A compiled model is needed for training but not necessary for predicting.
<br>
Optimizer used is "adam" and loss function as "categorical crossentropy". Metrics used is "accuracy".
<br>
Model fitting is the process where we train our model with training data.
<br>
Number of epochs is 30 and batch size as 16. Epochs is defined as the total number of iterations of all the training data in one cycle for training the machine learning model. 
<br>

### Hyperparamter Tuning 
The model is created as a function which tries various parameters, weights and biases to find the optimal paramaters for the model. We limit the tuning if it takes too long too achieve convergence. The best parameters are then selected based on their performance on validation data.
<br>

### Saving the model
Model is saved for further use.
<br>

### Visualisation
The predictions are visualised and classified as correct and incorrect predictions.
<br>

### Gradio Creation
Gradio Interface is created for seamless user experience.
Drag and Drop feature is introduced for submitting the image and predicting the image category.











# Team Members: 
# Keya Chakraborty (21BSR18010) 
https://github.com/keyachak25
# Parth Rajesh Achrekar (21BSR18046) 
https://github.com/Parth-Ach2002
# Dhruv Oli (21BSR18007)           
https://github.com/DhruvOli
# Debapratim Chakraborty (21BSR18004) 
https://github.com/DC-x-2003


