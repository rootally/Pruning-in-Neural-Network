# Pruning in Neural Network
Weight Pruning and Unit Pruning in Tensorflow

![alt text](https://github.com/rootally/Pruning-in-Neural-Network/blob/master/pruning.png)

## Given a layer of a neural network  are two well-known ways to prune it:
- Weight pruning: Set individual weights in the weight matrix to zero. This corresponds to deleting connections as in the figure above. Here, to achieve sparsity of k% I rank the individual weights in weight matrix W according to their magnitude (absolute value) , and then set to zero the smallest k%.

- Unit/Neuron pruning: Set entire columns to zero in the weight matrix to zero, in effect deleting the corresponding output neuron.
Here to achieve sparsity of k% we rank the the columns of a weight matrix according to their L2-norm  and delete the smallest k%.

## Try it on [Colab Notebook](https://colab.research.google.com/drive/1F1-06WLfr1OUo2QdYp_ySuXQvnSH5oPX)
