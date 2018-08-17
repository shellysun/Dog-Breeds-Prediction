# Dog-Breeds-Prediction

Descriptions:

The data was provided with a training set and a test set of images of dogs. Each image has a filename that is its unique 'id'. The dataset comparises 120 breeds of dogs.  

train folder - the training set, you are provided the breed for these dogs 
test folder - the test set, you must predict the probability of each breed for each image 
labels.csv - the breeds for the images in the train set

Goal:
The goal is build a higher accuracy model in order to create a classifier capable of determining a dog's breed from a photo.

Model choose:
For faster running, I choose Top 20 breeds instead of 120 breeds so that the accuracy should be better when will trian the whole dataset.

Method 1 Convolutional Neural Network Approach

Method 2 Transfer Learning Approach - VGG16

Method 3 Transfer Learning Approach - InceptionV3

Results:
Method 3 has the highest accuracy
