# Neural Network (Phase 1)
In this project, in the first part, I have implemented a Feed Forward neural network from scratch using the ```NumPy``` library.  In the second part, with the help of the codes of the first part, I have trained some neural networks on the given data and checked the effect of some parameters in the learning process.

## Dataset
The dataset is divided into two parts, train and test, 60,000 of which are for training and 15,000 for testing.  Each line of the data file is a vector of a flat image with a size of 784 (28 x 28).  Labels files contain label data.  Each label can be represented by one of the numbers 0 to 20, which represents one syllable.

## Data Classification
I have implemented and trained Feed Forward neural networks with different parameters using the ```FeedForwardNN``` class. I have designed a neural network with the following conditions:

 1. The value of learning rate should be 0.001.

 2. The number of epochs should be 20

 3. Batch_size is 64.

 4. The relu activator function is used in all layers.  (Except for the last layer which is identical.)
 
 5. I have used uniform initial weighting.
 
 ## Differnet Parameters Effect
In this project, I have checked the effect of different values of the following parameters on the network (by changing these parameters and re-running the relevant code section):

1. Learning rate

2. Activate function

3. Batch size

4. Epoch
