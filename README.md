# CNN-Dog-breed-identification
Using Neural network to identify Dog breed(Top 16 breed)

In this repository we have two kernels as below:

1)Dog breed identification using VGG16:- In this kernel I have applied transfer learning , I have used VGG16 pretrained model and designed the last FC layer manually which I have further connected to a softmax layer.
Using this I have acheived an acuracy of 94% with 4 epoch. Increasing the epochs might increase the efficiency further(you can try if you want!!)
In this kernal I have tried keeping a standard apporach so that the same code can be reused in other problems(ofcourse with minor tweeeks!!).

2)Dog breed with Multiple models:In this kernal we have used multiple pretrained models like VGG16,Xception,Inception to obtain a high accuracy. Inception has given us an accuracy of about 99.14%

Data Description

You are provided with a training set and a test set of images of dogs. Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs. The goal of the competition is to create a classifier capable of determining a dog's breed from a photo. 


File descriptions

train.zip - the training set, you are provided the breed for these dogs
test.zip - the test set, you must predict the probability of each breed for each image
sample_submission.csv - a sample submission file in the correct format
labels.csv - the breeds for the images in the train set

Data Link:

https://www.kaggle.com/c/dog-breed-identification/data


