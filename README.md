# Internship-task-
##Problem no.1
Requirements - Basic knowledge of PyTorch,Deep Learning, CNN,CIFAR-10 dataset,dataloaders,Tensors
Python libraries required - Torch,TorvhVision,matplotlib,numpy

PyTorch is a Machine Learning Library created by Facebook.
It works with tensors, which can be defined as a n-dimension matrix from which you can perform mathematical operations and build Deep Learning Models.
Deep Learning - This subfield of AI seeks to emulate the learning approach that humans use to obtain certain types of knowledge.
Deep learning can be seen as a way to automate predictive analytics.
CIFAR-10 Dataset - The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. 
There are 50000 training images and 10000 test images.
By using the classes method, we can get the image classes from the dataset.The label data is a list of 10,000 numbers ranging from 0 to 9, which corresponds to each of the 10 classes in CIFAR-10.
airplane : 0
automobile : 1
bird : 2
cat : 3
deer : 4
dog : 5
frog : 6
horse : 7
ship : 8
truck : 9
In order to train the model, two kinds of data should be provided at least. The image data should be fed in the model so that the model could learn and output its prediction. The label data should be provided at the end of the model to be compared with predicted output.These feeding data is called as Input.Each Input requires to specify what data-type is expected and the its shape of dimension. 
the dataset is divided into two groups: training and validation datasets.
We used a validation set with 10000 images (20% of the dataset). To ensure we get the same validation set each time, we set PyTorch’s random number generator to a seed value of 43. 
random_split method is used to create the training and validations sets.Dataloaders are created for training, validation and test sets.
An activation function is a function that is added into an artificial neural network in order to help the network learn complex patterns in the data. 
PReLu (Parametric ReLU) activation function is used.PReLU improves model fitting with nearly zero extra computational cost and keeps the areas of the negative axis. 
