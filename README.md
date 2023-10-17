# Libraryless-ML
Trying to code out some architectures without using most of the libraries - only using the 'time' module!

### Use nbviewer (https://nbviewer.org/) to view the truncated outputs!

Hence, most of these codes wouldn't be optimal due to not using vectorization and optimization concepts, but these are just for building them on my own!

Simple_MLP_Forward_Pass_Example :
This contains a simple example of just a forward pass with 2 layers, and only one training example, mainly to affirm the process.

Simple_MLP_Complete_Example : 
Extension of the previous notebook, here one step of complete backpropogation is done. Loss used is Binary Cross Entropy (BCE) and Activation function used is sigmoid. 
Further plans are to make a complete architecture for 'n' training examples, and giving the option to the user to decide the number of hidden layers, and neurons in each layer. Batch Gradient Descent is used since examples are less. 

Work of iris Dataset:

1) The first two notebooks contain the code for forward pass and one round of backward propogation on the last layer of the network.

2) The complete notebook codes out the entire process. I have set my own architecture, which can be changed in the notebook, and different hyperparamters as well.
   I have run the model on the dataset, for 1000 timesteps, and ended up with a loss of 50.1051 at the final timestep. Note that no optimization techniques    were used, and the architeture I used was only 5 layers, with neurons ranging from 3-5. Hence the architecture used was very small.
