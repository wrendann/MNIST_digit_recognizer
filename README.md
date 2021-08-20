# MNIST_digit_recognizer
This is an iPython Notebook that is used to recognize digits in the MNIST dataset in the Kaggle competition.

We begin by taking all of the data from the files provided by kaggle, and reshaping the pictures of the digits to be 28x28.

After importing the relevant libraries, we apply three blocks of a convolutional layer, a max pool layer, a dropout and batch normalization layer.

We then flatten the layers into single dimension, and use a neural network with regularization, dropout and batch normalization.

We use Adam optimizer, and appropriate loss functions. We apply early stopping and train the neural network.

As we can see, the training accuracy is less than the validation set accuracy. This must be influenced by the dropout layers we applied.

After testing this model on the test set, we find that it had a 99.125 % accuracy on the test set.
