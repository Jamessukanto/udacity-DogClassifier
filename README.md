## Assignment for Udacity Deep Learning Nanodegree
Original Repo: [project-dog-classification](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)  

The goal is to classify images into dog breeds with a CNN model, then transfer learning using VGG16. Image in, dog breed out. If supplied an image of a human, the algorithm will identify the resembling dog breed.

#### Import Datasets
Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)  
Download the [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) 
<br/>
<br/>
<br/>
## 01. Detect Human Faces
Assess accuracy of human face detector using haarcascade_frontalface_alt  
Accuracy: 99.0%

## 02. Detect Dogs
Assess accuracy of human face detector using a pretrained VGG16 Net  
Accuracy: 99.0%

## 03. Classify Dog Breeds using a CNN Model
Build and train a CNN model from scratch  
Accuracy: 11% (97/836), 30 epochs

## 04. Classify Dog Breeds using Transfer Learning
Model architecture that use part of a pre-trained VGG16  
Accuracy: 77% (644/836), 15 epochs
