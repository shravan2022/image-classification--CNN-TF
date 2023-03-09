# image-classification--CNN-TF
In this code, we load the CIFAR-10 dataset, which consists of 50,000 training images and 10,000 test images of 10 different classes. We normalize the pixel values between 0 and 1 and define the class names.

We then define a convolutional neural network (CNN) architecture using the Keras Sequential API. The model consists of several convolutional and pooling layers, followed by a few fully connected layers. We compile the model with an optimizer, loss function, and metrics.

We then train the model on the training data for a fixed number of epochs and validate it on the test data. We evaluate the model on the test data and print the test accuracy.

Finally, we use the model to make predictions on some new test images and plot the predictions along with the true labels for visualization.
