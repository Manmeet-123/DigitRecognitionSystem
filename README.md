# DigitRecognitionSystem

The Digit Recognition System is Used to recognise the handwritten digits. The building of the system involve following steps:

Step 1: Configuring the Project:
This step involve the setting up of python virtual environment and installing tensorflow and other libraries

Step 2: Importing the MNIST Dataset:
This step involves the importing of the MNIST digit dataset for the trainig purpose

Step 3: Defining the Neural Network Architecture:
The architecture of the neural network refers to elements such as the number of layers in the network, the number of units in each layer, and how the units are connected between layers.

Step 4: Building the TensorFlow Graph:
To build our network, we will set up the network as a computational graph for TensorFlow to execute. The core concept of TensorFlow is the tensor, a data structure similar to an array or list. initialized, manipulated as they are passed through the graph, and updated through the learning process.

Step 5: Training and Testing:
The training process involves feeding the training dataset through the graph and optimizing the loss function. Every time the network iterates through a batch of more training images, it updates the parameters to reduce the loss in order to more accurately predict the digits shown. The testing process involves running our testing dataset through the trained graph, and keeping track of the number of images that are correctly predicted, so that we can calculate the accuracy.
