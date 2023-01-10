# FaceMaskClassificationCNN
This is my Fall 2022 machine learning project. Our project idea was to create a convolutional neural network that can classify if a person has on a mask. 

Face mask detection CNN
Key’Shawn Billups, Aditya Shiroya, & Jiwoo Min​
 
As most people know covid-19 had a great impact on the way we currently live. Whether it's people being cleaner, taking colds more seriously, or wearing a mask. During the pandemic, stores implemented a mask policy, and some stores still have one. For our project to help stores with this we created a convolutional neural network model that can detect whether a person is wearing a mask or not. Face mask detection involves detecting the location of the face and then determining whether it has a mask on it or not. The issue is proximately cognate to general object detection to detect the classes of objects. Face identification categorically deals with distinguishing a specific group of entities i.e. Face. It has numerous applications, such as autonomous driving, education, surveillance, and so on. We found a dataset with around 12,000 images total, the dataset had 5000 no mask training images and 5000 with mask training images, 483 with mask and 509 without the mask of test data, 400 with mask and 400 without the mask of validation data. For our CNN we chose a sequential model with 3 convolutional and pooling layers, and 1 fully connected layer with 256 nodes. Lastly, it has an output layer with one because it is a binary classification. Sigmoid is used as the activation function at the end for the only node that gives the output of either 0 or 1.​ The optimizer is also applied with the purpose to reduce the cost calculated by cross-entropy.

For fitting and training data using CNN, 5 epochs came out to be the most proper number of epochs for our program to train the data and get high enough accuracy. After 5 epochs, we got accuracy of 0.9938 with loss of 0.0236 and the validation accuracy came out to be 0.9912 with loss of 0.0249.​
 
After constructing the model we were able to train it to approximately 97% on our test data. After training and testing, we computed a confusion matrix for our model.
