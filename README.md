# MAJOR-PROJ-mask-detection
FACE MASK DETECTION MODEL
(Masked and unmasked human classifier)
Step-:1
Download Dataset for face mask from (www.kaggle.com)
In dataset folder there is 2 folders (mask, unmask)

Step-:2
Import necessary libraries 

Steps-:3
initialize the initial learning rate, number of epochs, batch size and grab the list of images in our dataset directory, then initialize the list of data and class images 
Step -:4

First convert the data and labels to arrays, perform one-hot encoding on the labels. Then partition the data into training and testing splits using 80% of the data for training and the remaining 20% for testing and construct the training image generator for data augmentation 
 

Step-:5
load the MobileNetV2 network, ensuring the head FC layer sets then construct the head of the model that will be placed on top of the base model
compile our model
train the head of the network
 

Epoch-:
  

Print accuracy and loss in the model
 
Plot graph
 
Print the output
 
 
                                        MAJOR PROJECT
                                        Punyaslok swain
                                        punyaslokswain333@gmail.com  
