**NEURAL NETWORKS: ZERO TO HERO**
 
The spelled-out intro to neural networks and backpropagation: building micrograd

in this lecture:

What neural network training looks like under the hood

In particular we are going to start in a blank Jupyter notebook and we will define and train neural net.

We will see how things goes on under the hood and exactly sort of how on intuitive level.

Specifically we will go through building of micrograd.

**Micrograd**: An autograd engine short for automatic gradient. It implement backpropagration.

**Backpropagation**: Algorithm that allows you to efficiently evaluate the gradient of some kind of loss function with respect to the weights of a neural network

and what that allow us to do is we can iteratively tune the weights of that neural network to minimize the loss function and therefor improve the accuracy of the network.

So backpropagation would be at the mathematical core of any modern deep learning neural network library like pytorch.

The functionality of micrograd is best illustrated by an example:

