Image captioning project using (Xception model )for extracting features from the images and RNN model (LSTM- Long Short Term Memory). 

Xception is a pre-trained convolutional neural network model that was trained on the imagenet database. The Xception model is an extension of the inception Architecture and has outperformed other popular computer vision models such as Resnet50,VCG16,VCG19 and Inception V3.


LSTM are a popular kind of recurrent neural networks that was designed specifically to address the problem of short term memory that is popularly associated with traditional RNNs. This is why they are a perfect fit for this project.


The dataset used for this project is a kaggle dataset containing 8000 captioned images compiled from Flickr. 
The dataset can be downloaded from https://www.kaggle.com/adityajn105/flickr8k/activity.


Below are some images contained in the dataset. It is important to note that some images have more that one caption. See below an image from the dataset with 2 captions;
1: A child in a pink dress is climbing up a set of stairs in an entry way.
2. A girl going into a wooden building .So lets get into the deep learning implementation; 

This project was done using Google COLAB

Unzip and Data pre-processing (Cleaning, Lemmatization …)

Extract Features from the Images 

Create a training data generator

Build and Fit the Model to the Dataset

Test the Model
