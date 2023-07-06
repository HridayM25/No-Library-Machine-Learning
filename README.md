# Libraryless-ML
Trying to code out some architectures without using most of the libraries - only using the 'time' module.
Hence, most of these codes wouldn't be optimal due to not using vectorization concepts, but these are just for building them on my own!

Simple_MLP_Forward_Pass_Example :
This contains a simple example of just a forward pass with 2 layers, and only one training example, mainly to affirm the process.

Simple_MLP_Complete_Example : 
Extension of the previous notebook, here one step of complete backpropogation is done. Loss used is Binary Cross Entropy (BCE) and Activation function used is sigmoid. 
Further plans are to make a complete architecture for 'n' training examples, and giving the option to the user to decide the number of hidden layers, and neurons in each layer. Batch Gradient Descent is used since examples are used. 
