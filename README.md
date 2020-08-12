# Neural-Networks-for-MNIST-Data

In this project, we built neural networks of different architectures for MNIST digits classification as follows:

1) A neural network with 1 hidden layer of 30 sigmoid nodes, and an output layer10 softmax nodes from 1000 training images (100 images per digit). We train the network for 30 complete epochs, using mini-batches of 10 training examples at a time, a learning rate η=0.1. We then plot the training error, testing error, criterion function on training data set, criterion function on testing data set of a separate 1000 testing images (100 images per digit), and the learning speed of the hidden layer (the average absolute changes of weights divided by the values of the weights).

2) We implement the above with the following changes:
  - 2 hidden layers of 30 sigmoid nodes each
  - 3 hidden layers of 30 sigmoid nodes each, and with and without L2 regularization
  - 1 hidden layer with regularization
  - 2 hidden layers with regularization
  - 3 hidden layers with regularization
  
3) A convolutional neural network whose training is regularized through dropout. We augment a selection of 1000 images by rotating them for 1-3 degrees clockwise and counter clockwise, and shift them by 3 pixels in 8 different directions. 
